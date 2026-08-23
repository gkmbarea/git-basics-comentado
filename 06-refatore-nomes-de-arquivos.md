# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

remove arquivos do git e localmente

**Quando usar / observação:**

usar quando o arquivo nao deve mais existir no projeto

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

remove os arquivos do git mas os mantem localmente

**Quando usar / observação:**

quando quer remover do versionamento em grupo mas quer manter no seu computador

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

serve para renomear um arquivo ou mover um arquivo 
git mv [arquivo-original] [arquivo-renomeado] = este renomeia o arquivo
git mv [nome-do-arquivo] [local-destino (docs/downloads)]

**Quando usar / observação:**

quando se quer renomear um arquivo ao inves de apagar o arquivo antigo e commitar um arquivo novo

---

## Checklist deste arquivo

- [ x] 1. `git rm [arquivo]`
- [ x] 2. `git rm --cached [arquivo]`
- [ x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
