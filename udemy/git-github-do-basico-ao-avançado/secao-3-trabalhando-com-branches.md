# Seção 3 - Trabalhando com branches

## Aula 36 - O que são branches?

- É uma ramificação do projeto
- Trabalhamos com diversas branches em um projeto
- Branch é a forma que o git separa as versões do projeto
- O projeto inicia na branch main
- Geralmente, cada nova feature de um projeto fica em uma branch separada
- Após a finalização das alterações, as branches são unidas para ter o código fonte final

## Aula 37 - Criando e visualizando branches

- git branch: permite criar uma branch e visualizar as branchs disponiveis

## Aula 38 - Deletando branches

- usamos a flag -d ou --delete para deletar uma branch
- não é comum deletrar uma branch, normalmente guardamos o histório
- normalmente deletamos uma branch que foi criado errado

## Aula 39 - Mudando de branch

- git checkout -b: permite mudar para outra branch
- também é utilizado para dispensar mudanças de um arquivo
- é preciso tomar cuidado pois, alterar a branch pode levar alterações que não foram commitadas, para a branch errada

## Aula 40 - Unindo branches

- git merge: permite unir o código de dois branches distintos
- normalmente é por meio dele que recebemos as atualizações de outros dev

## Aula 41 - Utilizando a stash

- git stash: permite salvar as modificações atuais para prosseguir com uma outra abordagem de solução e não perder o código
- após o comando, a branch será resetada para a versão de acordo com o repo

## Aula 42 - Recuperando stash

- git stash list: permite verificar as stashs criadas
- git stash: permite recuperar a stash
- podemos continuar de onde paramos com os arquivos adicionados a stash 

## Aula 43 - Removendo a stash

- git stash clear: remover todas as stashs de uma branch
- git stash drop: caso seja necessario deletar uma stash especifica

## Aula 44 - Criando tags

- tag se assemelha a stash, mas define marcos desenvolvimento 
- git tag -a -m
- é utilizado para demarcar estágios de desenvolvimento de algum recurso

## Aula 45 - Alterando a tag

- git show: mostra tags
- git checkout: trocar de tags
- esses dois comandos permitem retroceder ou avançar em checkpoints de uma branch

## Aula 46 - Enviando tags ao repositório

- as tags podem ser enviadas para o repositório do código e compartilhadas na equipe
- git push origin
- se quiser enviar mais tags pode usar git push origin --tags
