<div align="center">

# 🌳 Learn Git Branching

</div>


## 📌 Sobre a plataforma

O **Learn Git Branching** é um site gratuito, criado por Peter Cottle, que ensina Git de forma visual e interativa. Ele simula um repositório Git direto no navegador, sem instalar nada: a cada comando digitado no terminal, a **árvore de commits** ao lado é atualizada para mostrar o efeito na hora. Além do modo sandbox para experimentar livremente, a plataforma tem uma série de **níveis** com objetivos específicos, organizados em sequências que vão dos conceitos básicos (commit, branch, merge e rebase) até tópicos avançados e trabalho com repositórios remotos (clone, fetch, pull e push). O site está disponível em português do Brasil.

---

## 🗃️ Sobre o repositório

Esta pasta reúne os **meus estudos no Learn Git Branching**. Faz parte do repositório **linux-study-log**, onde registro meus estudos de Linux e ferramentas relacionadas em diversas plataformas. Aqui guardo o registro das sequências de níveis feitas, com anotações pessoais dos comandos praticados e das dúvidas que surgiram pelo caminho.

---

## 📋 Registro das sequências

### Aba Main

| # | Sequência | Principais conceitos | Status |
|---|-----------|----------------------|--------|
| 01 | Introdução | `git commit`, `git branch`, `git merge`, `git rebase` | 🔄 |
| 02 | Subindo de nível | Movimentação entre commits (`HEAD`, `^`, `~`), `reset`, `revert` | 🔄 |
| 03 | Movendo trabalho por aí | `cherry-pick`, rebase interativo | 🔄 |
| 04 | Miscelânea | Pegar um único commit, tags, `git describe` | 🔄 |
| 05 | Tópicos avançados | Rebase em múltiplos branches, múltiplos pais | 🔄 |

### Aba Remote

| # | Sequência | Principais conceitos | Status |
|---|-----------|----------------------|--------|
| 06 | Push & Pull: Git remotes | `clone`, `fetch`, `pull`, `push`, branches remotos | 🔄 |
| 07 | Para a origem e além | Argumentos de `push` e `fetch`, rastreamento de branches remotos | 🔄 |

**Legenda:** 🔄 pendente · 🟧 em andamento · ✅ concluída

---

## 🗂️ Como organizo os diretórios

Uma pasta para a plataforma, com um arquivo de anotações por sequência, numerado na mesma ordem do site:

```
linux-study-log/
├── ...
└── learn-git-branching/
    ├── main-01-introducao.md
    ├── main-02-subindo-de-nivel.md
    ├── ...
    ├── remote-06-push-e-pull.md
    └── README.md
```

Cada arquivo traz:

- 📝 Resumo dos comandos e conceitos com minhas palavras
- 💻 Comandos usados para resolver cada nível

---

## 🔗 Links úteis

- [Learn Git Branching](https://learngitbranching.js.org/?locale=pt_BR): site oficial da plataforma, em português do Brasil
- [Repositório do projeto no GitHub](https://github.com/pcottle/learnGitBranching): código-fonte do site
- [Voltar ao repositório principal](../README.md)