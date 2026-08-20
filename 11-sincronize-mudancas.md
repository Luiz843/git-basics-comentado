# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

* Baixa os commits da branch remota para a local

**Quando usar / observação:**

* Quando se deseja carregar as alterações da remoto para a local.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

* Faz o merge da branch remota com a branch atual

**Quando usar / observação:**

* Quando se deseja carregar as alterações na branch local

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

* Envia os arquivos locais para o remoto.

**Quando usar / observação:**

* Quando se deseja enviar as alterações

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

* Faz o fetch + o merge em um unico comando.

**Quando usar / observação:**

* Quando se deseja fazer o fatch e o merge em um unico comando

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
