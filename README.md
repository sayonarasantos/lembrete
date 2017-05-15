# lembrete
### Comandos

- git init    __//cria repositorio__

- git status

- git add .   __//Working Directory --> Index (atualiza área temporária)__
- git commit -m "mensagem"    __//Index --> HEAD (atualiza repositório local)__
- git commit -a -m "mensagem"   __//add + commit__

- git clone endereço    __//clona repositório remoto__

- git push origin master    __//Repositório local ---> Repositório remoto (envia as atualizações)__
- git pull origin master    __//Repositório remoto --> Repositório local (traz as atualizações)__

---

### Como criar repositório com material já existente
- cria repositório no github/bitbucket
- git remote add origin endereço
- git push -u origin master

---

### Como configurar identificação
- git config --global user.email "email"
- git config --global user.name "Nome"

---

### Como colaborar
- fork
- realiza as edições: clone, add, commit, push...
- new pull request
