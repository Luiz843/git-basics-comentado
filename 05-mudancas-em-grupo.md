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

* Lista as branchs locais

**Quando usar / observação:**

* Quando se deseja visualizar as branchs locais.

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

* Cria uma nova branch.

**Quando usar / observação:**

* Quando se deseja criar uma nova branch.

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

* Pula para a branch e realiza o git pull junto, atualizando a branch.

**Quando usar / observação:**

* Quando se deseja pular para uma branch existente e atualizar com a versão "remota".

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

* Realiza o merge da branch citada com a branch atual.

**Quando usar / observação:**

* Quando se deseja juntar as alterações de uma branch com a atual.

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

* Excluir a branch localmente.

**Quando usar / observação:**

* Quando quiser excluir a branch local.

---

## Checklist deste arquivo

- [x] 1. `git branch`
- [x] 2. `git branch [nome-do-branch]`
- [x] 3. `git switch -c [nome-do-branch]`
- [x] 4. `git merge [nome-do-branch]`
- [x] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
