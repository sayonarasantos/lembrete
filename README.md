# lembrete
### Comandos

- git init   ` cria repositorio`

- git status

- git add .   
> Working Directory --> Index (atualiza área temporária)
- git commit -m "mensagem"    __//Index --> HEAD (atualiza repositório local)__
- git commit -a -m "mensagem"   __//add + commit__

- git clone endereço    __//clona repositório remoto__

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
