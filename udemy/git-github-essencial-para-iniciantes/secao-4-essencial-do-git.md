# Seção 4 - Essencial do Git

## Aula 9 - Ciclo de vida do Git

- Normalmente teremos um repositório local, na máquina, e um repositório remoto, o repositório central no GitHub
- O Git possui uma área chamada staging, que representa uma área de preparação e permite organizar como as versões são separadas, comentadas e registradas
- `git add`: coloca o arquivo na área de staging
- `git commit`: registra oficialmente a versão do arquivo que estava no staging
- Fluxo básico: arquivo modificado → `git add` (staging) → `git commit` (repositório local) → `git push` (repositório remoto)

## Aula 10 - Criando repositório Git localmente em sua máquina

- Repositório no Git é uma pasta onde todos os arquivos do projeto são armazenados
- `git init`: torna a pasta um repositório gerenciado pelo Git
- Uma pasta oculta `.git` é criada
- Evite usar, editar ou excluir os arquivos da pasta `.git`, pois isso pode afetar o projeto

## Aula 11 - Ciclo de vida na prática usando Git localmente

- `git status`: permite ver o estado atual do repositório
- É uma boa prática incluir comentários nos commits
- `git commit -m "comentário explicando o que foi feito"`: registra o commit com uma mensagem
- Exemplo de fluxo: `git status` → `git add .` → `git commit -m "adiciona arquivo inicial"`

## Aula 12 - Vendo os históricos do seu repositório Git

- `git log`: mostra o histórico do que foi registrado, com autor, data, mensagem e hash de cada commit
- `git log --oneline`: mostra o histórico de forma resumida, com um commit por linha
