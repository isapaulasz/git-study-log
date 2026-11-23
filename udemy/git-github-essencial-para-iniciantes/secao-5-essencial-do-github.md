# Seção 5 - Essencial do GitHub

## Aula 13 - Ciclo de vida na prática usando o GitHub

- Criando um novo repositório diretamente no GitHub, usando `New repository`
- Durante a criação do repositório, defina:
  - nome
  - descrição
  - privacidade (público ou privado)
  - adicionar arquivo `README`
  - adicionar arquivo `.gitignore`
  - escolher licença
- É possível criar primeiro o repositório local ou primeiro o repositório remoto, e a ordem dos comandos muda dependendo da escolha
- `git remote add origin https://github.com/usuario/repositorio.git`: com o repositório local criado, conecta-o ao repositório remoto
- É preciso gerar um token de acesso pessoal (Personal Access Token) no GitHub para se autenticar, pois a senha da conta não é mais aceita nos envios via HTTPS
- `git branch -M main`: renomeia a branch atual para `main`, o nome padrão atual (o curso utiliza `master`)
- `git push -u origin main`: envia o projeto para o repositório remoto (`origin`) na branch principal
- A flag `-u` associa a branch local à remota, então nos próximos envios basta usar `git push`

## Aula 14 - Clonando repositório com GitHub

- Outros usuários podem ver seus projetos no GitHub, o que inclui fazer download e clonar o projeto
- `git clone https://github.com/usuario/repositorio.git`: clona um repositório para sua máquina
- O comando cria uma pasta com o nome do repositório, já com o histórico completo e conectada ao remoto (`origin`)

## Aula 15 - Usando Git em interface gráfica com GitHub Desktop

- O GitHub possui a ferramenta GitHub Desktop
- É uma interface visual para trabalhar com Git sem usar o terminal
- Download do GitHub Desktop: https://desktop.github.com/download/
- Via GitHub Desktop é possível criar repositórios, clonar e adicionar repositórios que já existem no Git da sua máquina
