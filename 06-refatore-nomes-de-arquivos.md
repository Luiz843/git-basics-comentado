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

* Remove o arquivo

**Quando usar / observação:**

* Quando se deseja remover um arquivo

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

* Remove o arquivo do commit mas fica na area de arquivos nao adicionados ao commit.

**Quando usar / observação:**

* Quando se commitou algo errado.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

* Renomeia um arquivo

**Quando usar / observação:**

* Quando se quer renomear um arquivo

---

## Checklist deste arquivo

- [X] 1. `git rm [arquivo]`
- [X] 2. `git rm --cached [arquivo]`
- [X] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
