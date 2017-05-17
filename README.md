# lembrete

### Comandos

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

### Como criar referência do repositório remoto
  (Caso já exista um diretório local com arquivos)

- criar repositório remoto no github/bitbucket sem arquivo (sem readme)

- criar repositório local no diretório dos arquivos (git init)

- adicionar a referência remota do repositório com o comando: git remote add origin endereço_do_repositório_remoto
  > comando original: git remote aplido_da_referencia endereço_do_repositório_referenciado

- enviar os arquivos ao repositório remoto (add, commit, push)

---

### Como configurar identificação

- Email do github: git config --global user.email "email"

- Nome de usuário: git config --global user.name "Nome"

---

### Como colaborar

- Criar uma cópia do projeto no meu git com *fork*

- realizar as modificações: clone, add, commit, push...

- solicitar a adição das modificações no projeto principal: *new pull request*
