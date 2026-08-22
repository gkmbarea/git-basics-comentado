# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Mostra em qual branch voce esta, se tem commits a serem feitos ex: "tem 2 arquivos modificados e nao comitados"

**Quando usar / observação:**

Quando nao se lembra em qual branch voce esta ou verificar se ha alguma pendencia

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

mostra todas diferencas do arquivo que ainda nao foram preparas ou seja, nao foram pro git add ainda

**Quando usar / observação:**

quando voce quer ver as modificacoes feitas que nao foram preparadas ainda

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

prepara o arquivo para ser commitado

**Quando usar / observação:**

voce terminou de modificar no arquivo salvou e agora vai querer comitar voce da git add . para mandar todos arquivos da branch para o preparo do commit ou apenas o arquivo em especifico como um git add faca-mudancas.md

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

mostra as mudancas que voce ja fez com git add e estao preparadas para o commit

**Quando usar / observação:**

usar antes de fazer um commit para ver todas modificacoes  

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

retira o arquivo da area de preparacao

**Quando usar / observação:**

o arquivo precisa ser modificado novamente ou esta incompleto

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

este gera o commit com sua mensagem do porque o arquivo foi alterado e gera a id do commit

**Quando usar / observação:**

quando voce terminar as modificacoes que precisava naquela brunch, para commitar e depois dar push para o github.

---

## Checklist deste arquivo

- [ x] 1. `git status`
- [ x] 2. `git diff`
- [ x] 3. `git add [arquivo]`
- [ x] 4. `git diff --staged`
- [ x] 5. `git reset [arquivo]`
- [ x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
