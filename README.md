# lembrete
### Comandos

- git init
  > cria repositório

- git status

- git add .
  > adiciona todos os arquivos atualizados na área temporária (Working Directory --> Index)
  
- git commit -m "'mensagem de descrição'"
  > atualiza repositório local (Index --> HEAD)
  
- git commit -a -m "mensagem de descrição"
  > add + commit

- git clone 'endereço'
  > clona repositório do endereço informado

- git push origin master    __//Repositório local ---> Repositório remoto (envia as atualizações)__
- git pull origin master    __//Repositório remoto --> Repositório local (traz as atualizações)__

---

### Como referenciar repositório local ao remoto
- criar repositório remoto no github/bitbucket
- criar repositório local
- git remote add origin endereço_do_remoto
>- git push -u origin master

---

### Como configurar identificação
- git config --global user.email "email"
- git config --global user.name "Nome"

---

### Como colaborar
- fork
- realizar as edições: clone, add, commit, push...
- new pull request
