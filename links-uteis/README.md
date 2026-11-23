# 🔗 Links Úteis

## 📌 Sobre o repositório

Esta pasta guarda os links, artigos e documentações que encontro pelo caminho e que valem a pena revisitar. Cada link vem acompanhado de um breve resumo do que ele ensina, para facilitar a consulta depois.

> 🚧 A lista cresce conforme eu estudo: novos links entram com o tempo.

---

## 📝 Conventional Commits

🔗 [conventionalcommits.org/pt-br/v1.0.0](https://www.conventionalcommits.org/pt-br/v1.0.0/)

Especificação de uma convenção simples para escrever mensagens de commit, com o formato `tipo(escopo opcional): descrição`, seguido de corpo e rodapé opcionais. A página explica os tipos principais, como `feat` e `fix`, além de outros usados com frequência, como `docs`, `refactor` e `test`. Também mostra como indicar mudanças que quebram compatibilidade (`BREAKING CHANGE` ou o símbolo `!`), traz exemplos prontos e relaciona a convenção ao versionamento semântico (SemVer). Em resumo, ajuda a manter um histórico legível e facilita automações, como a geração de changelogs.

---

## 📋 Criando um template de Pull Request no GitHub

🔗 [docs.github.com: Creating a pull request template for your repository](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository)

Documentação oficial do GitHub (em inglês) que ensina a criar um template que preenche automaticamente a descrição de novos Pull Requests. O passo a passo mostra onde o arquivo `pull_request_template.md` pode ficar (raiz, pasta `docs` ou `.github`) e como criar vários templates em uma pasta `PULL_REQUEST_TEMPLATE`. Também sugere o que incluir no modelo, como referência a issues, descrição das mudanças e menção de quem vai revisar. Vale lembrar que o template só passa a valer para os colaboradores depois de entrar na branch padrão do repositório.

---

## 🌿 Git Flow: o que é, quando utilizar e como funciona

🔗 [alura.com.br: Git Flow, o que é, quando utilizar e como funciona](https://www.alura.com.br/artigos/git-flow-o-que-e-como-quando-utilizar)

Artigo da Alura que apresenta o Git Flow, um fluxo de trabalho criado em 2010 para organizar branches em equipe. Ele explica o papel de cada branch (`main`, `develop`, `feature`, `release` e `hotfix`) e mostra os comandos para criar e finalizar cada uma, tanto com o Git puro quanto com a CLI `git-flow`. O texto também discute vantagens, como desenvolvimento paralelo e correções de emergência seguras, e desvantagens, como a complexidade e a pouca afinidade com entrega contínua. Por fim, cita alternativas como GitHub Flow, Trunk-Based Development e GitLab Flow.