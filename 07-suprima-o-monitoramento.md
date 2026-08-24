# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

ele diz ao git quais arquivos e pastas devem ser ignorados, evitando que sejam incluidos no controle de versao.

**Quando usar / observação:**

quando nao quer adicionar algum arquivo ou pasta ao versionamento, como logs etc.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

Lista arquivos não rastreados pelo Git que foram ignorados pelas regras padrão.
`--others` seleciona arquivos que ainda não foram adicionados ao controle de versão.
`--ignored` mostra os arquivos ignorados, e `--exclude-standard` considera regras do `.gitignore`.



**Quando usar / observação:**

Use para conferir quais arquivos estão sendo ignorados antes de revisar ou alterar o `.gitignore`.

---

## Checklist deste arquivo

- [ x] 1. Arquivo `.gitignore`
- [ x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
