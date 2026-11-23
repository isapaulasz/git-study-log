# Seção 4 - Compartilhamento e atualização de repositórios

## Aula 51 - Encontrando branches

- git fetch: atualiza todas as branches e tags que ainda não estão reconhecidos no seu repositório local
- branches novas são criadas todo o tempo, e seu git pode não estar mapeando eles
- 

## Aula 52 - Recebendo atualizações

- git pull: recebe atualizações do repositório remoto
- atualiza a branch
- quando trabalhamos em equipe, recebemos atualizações de outros membros

## Aula 53 - Enviando alterações

- git push: envia atualizações e alterações para o repo remoto
- permite compartilhar as atualizações com a equipe ou salvar ao fim da tarefa

## Aula 54 - Utilizando o remote

- git remote: permite adicionarou remover um repo para trackear
- git remote add origin: adiciona o repositorio remoto ao git local

## Aula 55 - Conhecendo submodules

- Submodules é a maneira que temos de possuir dois ou mais projetos em um só repositório
- git submodule add: adiciona os submodulos
- git submodule: verifica os submodulos
- podemos adicionar uma dependencia ao projeto atual, mantendo suas estruturas separadas

## Aula 56 - Atualizando os submodules

- para atualizar um submodulo, primeiro devemos commitar as mudanças
- git push --recurse-submodule=on-demand: envia para o repo do submodulo utilizado
- esse fluxo fará a atualização apenas do submodulo
