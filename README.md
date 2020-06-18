# lembrete

### Áreas

- Working Directory: contém os arquivos correntes, os arquivos manuseados
- Index: área temporária, onde preperam-se os arquivos que irão compor o próximo commit
- Head: aponta para a versão mais atualizada do branch, a que possui o último commit

Obs.: Um repositório pode possuir vários branches, ramificações de um projeto, e o Head aponta para versão atual do branch corrente.

---

### Comandos mais utilizados

- git clone endereço_do_repositório
  > clona repositório do endereço informado
  
- git add remote origin endereço_do_repositório
  > cria uma conexão (referência) com um repositório remoto

- git init
  > inicializa repositório

- git status
  > verifica o estado dos arquivos 

- git add arquivo_modificado
  > adiciona o arquivo modificado na área de seleção (Working Directory --> Index)
  
- git add .
  > adiciona todos os arquivos modificados na área de seleção (Working Directory --> Index)
  
- git commit -m "mensagem de descrição"
  > atualiza o branch (Index --> HEAD)

- git push origin master
  > envia as atualizações do repositório master ao repositório remoto origin (Repositório master --> Repositório origin)
  
- git pull origin master
  > traz as atualizações do repositório remoto origin (Repositório origin --> Repositório master)
  
- git checkout -b novo_branch
  > cria um novo branch do projeto

- git checkout branch_X
  > aponta para o branch em que se quer trabalhar, branch_X

- git merge branch_Y
  > traz as atualizações de outro branch (branch_Y) para o branch ativo
  
- git diff branch_Y branch_X
  > mostra as diferenças entre os branches

---

### Configuração global - identificação

- Email do github:
```
git config --global user.email email_do_usuário
```

- Nome de usuário:
```
git config --global user.name "Nome do usuário"
```

---

### Como clonar um repositório remoto vazio

```
  git clone endereço_do_repositorio_remoto
  cd nome_do_projeto
  touch README.md
  git add README.md
  git commit -m "add README"
  git push -u origin
```

---

### Como criar uma conexão remota para seu repositório local

- Crie um repositório remoto no github/bitbucket sem arquivo (sem readme)

- Adicione a referência do repositório remoto
```
git remote add aplido_da_referencia endereço_do_repositório_remoto
```
- Envie os arquivos do repositório local ao remoto (add, commit, push)

---

### Como colaborar

- Crie uma cópia do projeto principal no meu git, clicando em `fork`

- Realize as modificações desejadas: clone, add, commit, push...

- Solicite a adição das modificações no projeto principal, clicando em `new pull request`
