# lembrete

### Comandos mais utilizados

- git init
  > cria repositório

- git status
  > verifica o estado dos arquivos 

- git add .
  > adiciona todos os arquivos atualizados na área de seleção (Working Directory --> Index)
  
- git commit -m "mensagem de descrição"
  > atualiza repositório local (Index --> HEAD)
  
- git commit -a -m "mensagem de descrição"
  > add + commit

- git clone endereço
  > clona repositório do endereço informado

- git push origin master
  > envia as atualizações ao repositório remoto origin (Repositório local ---> Repositório remoto)
  
- git pull origin master
  > traz as atualizações do repositório remoto origin (Repositório remoto --> Repositório local)

---

### Configuração global - identificação

- Email do github: git config --global user.email "email"

- Nome de usuário: git config --global user.name "Nome"

---

### Criação de um novo repositório
Clone de um repositório remoto vazio
- git clone endereço_do_repositorio_remoto/nome_do_projeto
- cd nome_do_projeto
- touch README.md
- git add README.md
- git commit -m "add README"
- git push -u origin

---

### Como criar referência do repositório remoto
  (Caso já exista um diretório local com arquivos)

- Criar um repositório remoto no github/bitbucket sem arquivo (sem readme)

- Criar um repositório local no diretório dos arquivos (git init)

- Adicionar a referência remota do repositório com o comando: git remote add origin endereço_do_repositório_remoto
  > comando original: git remote aplido_da_referencia endereço_do_repositório_referenciado

- Enviar os arquivos ao repositório remoto (add, commit, push)

---

### Como colaborar

- Criar uma cópia do projeto principal no meu git, clicando em `fork`

- Realizar as modificações: clone, add, commit, push...

- Solicitar a adição das modificações no projeto principal, clicando em `new pull request`
