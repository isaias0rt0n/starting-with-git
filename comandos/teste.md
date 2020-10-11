# :computer:

### Comandos 

- git init -  cria um novo repositório do Git
- git add - Adiciona mudanças ao index
- git status - Checa o estado atual do repositório. Verifica se repositório está com o atual estado do diretório de trabalho ou se existem modificações a serem gravadas.
- git commit -m "mensagem de commit" - Confirmar as mudanças feitas, passando uma mensagem para indentificar a mudança
- git config --list - mostras todas as configurações específicas do seu git 
- git config --global user.name "nome_usuario" - Define um nome de usuário do Git para todos os repositórios no seu ambiente local
- git config --global user.email "seuemail@email.com" - Define seu email do Git para todos os repositórios no seu ambiente local
- git config --global user.nickname "seu_nick" - Define seu nick do Git para todos os repositórios no seu ambiente local
- git config --global --unset "user.atributo" - Remove algum atributo das configurações (ex:git config --global --unset user.email)
- git remote add origin https://seu-link-do-repositorio.git - Aponta o nosso repositório local para o repositório remoto. 
  - O "origin" é o nome do repositório remoto padrão em que se criou localmente através do clone
- git remote -v  - Lista os meus repositórios remotos cadastrados
- git push origin master - "Empurra" o nosso repositório local para o remoto (GitHub, nesse caso)
- git pull origin master - "Pega" o nosso repositório remoto para o local.
- git clone https://link-projeto-github.git - Clona um repositório do GitHub para nossa maquina local. Pode ser para contribuir, alterar, usar, etc.
