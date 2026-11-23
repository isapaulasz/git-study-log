# Seção 2 - Git Fundamental 

## Aula 17 - O que é um repositório

- é onde o código será armazenado
- cada projeto tem um repositório
- quando criamos um repositório estamos iniciando um projeto
- o repositório pode ir para servidores que são especializados em gerencia-los, como githube bitbucket
- cada desenvolvedor pode baixar o repositório e criar versões diferentes em sua máquina

## Aula 18 - Criando um repositório

- git init: criar um repositorio na pasta atual
- o git cria a pasta ocupa .git com os arquivos necessarios pra iniciar o repositorio
- o diretório agora é reconhecido pelo git como um projeto

## Aula 19 - O que é GitHub

- É um serviço para gerenciar repositórios
- Permite enviar projetos para o github e disponibiliza-los publicamente

## Aula 21 - Enviando repositório para o GitHub

- precisamos primeiro criar o projeto no github, inicializar no git em nossa máquina e depois sincronizar com o github
- só precisamos fazer isso uma vez por projeto
- git status
- git add .
- git commit -m ""
- git branch -m master
- Agora a regra é usar o termo main ao invés de master
- git remote add origin
- git push -u origin master

## Aula 22 - Verificando alterações

- git status: usado para verificar mudanças
- Os arquivos são mapeados como não monitorados e modificados

## Aula 23 - Adicionando arquivos ao projeto

- git add: para adicionar arquivos novos
- podemos adicionar de 1 até vários arquivos, incluindo todos
- adicionando eles passam a ser monitorados pelo git
- git add . : adiciona tudo

## Aula 24 - Salvando alterações

- git commit: salva as alterações
- podemos commitar arquivos específicos ou vários usando a flag -a
- É uma boa prática fazer o commit com uma mensagem explicando as alterações
- A mensagem pode ser adicionada com a flag -m

## Aula 25 - Enviando código para o repositório

- git push: envia o código para o repositório remoto
- o código no servidor é atualizado com base no código enviado

## Aula 26 - Recebendo alterações

- git pull: sincroniza o código local com as mudanças do repositório remoto
- O comando busca atualizações, e faz a união ao codigo local

## Aula 27 - Clonando repositórios

- git clone: clonar um repositório
- é o ato de baixar um repositório do servidor remoto
- comumente utilizado quando entramos em um novo projeto

## Aula 28 - Removendo arquivos

- git rm: deletar arquivos da monitoração do git
- após deletar um arquivo do git, ele não terá mais suas atualizações consideradas pelo git
- é possivel adicionar novamente com git add e git commit

## Aula 29 - Verificando as alterações por meio de log

- git log: permite acessas um log de modificações
- apresenta informações dos commits realizados

## Aula 30 - Renomeando arquivos

- git mv: permite mover ou renomear arquivos
- ao mover, o novo arquivo é monitorado pelo git, e o anterior é excluido

## Aula 31 - Desfazendo alterações

- git checkout: permite que o arquivo modificado seja retornado ao estado original
- após a utilização, o arquivo sai do staging
- com novas alterações, o arquivo retorna ao staging

## Aula 32 - Ignorando arquivos e diretórios em um projeto

- .gitignore: arquivo criado na raiz do projeto, utilizado para ignorar arquivos do projeto
- útil para arquivos gerados automaticamente ou arquivos com informações sensíveis

## Aula 33 - Resetando uma branch

- git reset: resetar todas as mudanças feitas, inclusive commitadas
- geralmente é utilizado com a flag --hard, reseta o branch e perde tudo
- 
