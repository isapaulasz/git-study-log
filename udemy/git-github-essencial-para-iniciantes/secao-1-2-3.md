# Seção 1 - Introdução

## Aula 1 - Apresentação do curso de Git e GitHub

- Grandes empresas exigem grandes grupos de pessoas trabalhando simultaneamente em um mesmo código
- Versionamento é a base para lidar com grupos de diversas pessoas trabalhando em um mesmo projeto
- As principais ferramentas são Git e GitHub

# Seção 2 - Entendendo o que é uma versão com Git e GitHub

## Aula 3 - O que é uma versão quando se fala de Git?

- Versionar vem de versões
- Versão pode ser entendida como o registro do seu projeto em momentos diferentes do seu desenvolvimento
- Versionamento registra essas diversas versões e permite retornar a qualquer uma delas a qualquer momento
- Git é uma ferramenta de versionamento

## Aula 4 - Controle de versão - Git

- É comum trabalhar com múltiplas versões sem aplicar versionamento, como na prática de criar cópias de arquivos de texto (`relatorio_final.docx`, `relatorio_final_v2.docx`, etc.)
- Ferramentas como o Google Docs já aplicam versionamento em seus documentos
- É possível retornar a versões anteriores do documento e recuperar atualizações perdidas
- Porém, para o desenvolvimento de software, é necessária uma ferramenta mais completa
- O Git permite versionar diversos tipos de arquivos na sua máquina

## Aula 6 - Git e seu sistema de controle de versão distribuído

- Foi desenvolvido em 2005 por Linus Torvalds, criador do Linux
- Em um sistema distribuído, cada desenvolvedor tem uma cópia completa do projeto, com todo o histórico, em sua máquina
- É necessário criar um repositório para versionar o projeto no Git
- Para trabalhar em equipe, é necessário interagir com um repositório central
- O GitHub é um exemplo de serviço que hospeda repositórios centrais

## Aula 7 - O que é GitHub?

- O GitHub é uma rede social de desenvolvedores
- O nome une Git (o sistema de versionamento) e Hub (ponto central de conexão entre pessoas e projetos)
- Além de hospedar repositórios, permite registrar e expor projetos publicamente

# Seção 3 - Instalação do Git na sua máquina

- Link para download e instalação: https://git-scm.com/
- `git --version`: exibe a versão do Git instalada na máquina
- `git config --global user.name "seu nome"`: configura o nome do usuário
- `git config --global user.email "seu email"`: configura o e-mail do usuário
- `git config user.name`: exibe o nome do usuário configurado
- `git config user.email`: exibe o e-mail configurado
- `git config --list`: exibe todas as configurações atuais
- Nome e e-mail são registrados em todos os commits feitos
- `git config --global init.defaultBranch main`: define `main` como nome padrão da branch inicial nos novos repositórios
