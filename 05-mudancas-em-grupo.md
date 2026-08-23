# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

voce consegue listar todas as ramificacoes(branches) locais  do repositorio atual.
**Quando usar / observação:**

imagino que usamos para ver quais branches estao no local e tambem mostrar em qual branch voce esta atualmente 

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**
cria uma nova branch e escreve o nome dela


**Quando usar / observação:**

quando voce quiser fazer uma nova branch para modificar um arquivo em especifico

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

Ele muda para a brench especificada e o arquivo modificado so aparece naquela branch

**Quando usar / observação:**

quando voce quer testar uma modificacao em uma brench sem modificar esta brench atual, voce cria outra brench por exemplo e este arquivo em especifico so aparecera la

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

junta o historico da brench especificada a brench atual

**Quando usar / observação:**

quando voce ja terminou as modificacoes necessarias nas duas brenchs
---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**
exclui a branch especificada

**Quando usar / observação:**

quando voce ja concluiu todas modificacoes necessarias e nao vai mais usar aquela branch

---

## Checklist deste arquivo

- [ x] 1. `git branch`
- [ x] 2. `git branch [nome-do-branch]`
- [ x] 3. `git switch -c [nome-do-branch]`
- [ x] 4. `git merge [nome-do-branch]`
- [ x] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
