# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

* Move a branch de volta ao commit porem preserva as alterações

**Quando usar / observação:**

* Quando se deseja apontar para um commit sem perder as alterações

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

* Move a branch para o commit mas apaga o que veio de alteração depois

**Quando usar / observação:**

* Quando se deseja ir para um commit e descartar as alterações

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
