## Comandos do git


#### iniciar o git na aplicação
```bash
git init
```

#### Colocar diretório em que seu repositório está armazenado.
```bash
git remote add origin <URL do repositorio: https://github.com/pl4kill/Use.Git..git>
```

### Clonar repositório github
```bash
git clone <URL do repositorio: https://github.com/pl4kill/Use.Git..git>
```

### verificar o que foi alterado
```bash
git status
```

### adicionar alteraçoes na staging area
```bash
# "." podendo ser tbm o nome do arquivo
git add . 
```

### salvar alterações
```bash
## MSG sendo sua mensagem
git commit -m "MSG"
```

### Enviar os commits de sua branch e repositório Git local para o seu repositório remoto.
```bash
## MSG sendo sua mensagem
git push -u origin master
```

### listar branches
```bash
git branch
```

### criar uma branch
```bash
# sendo NAME o que nome que quero para minha branch
git checkout -b NAME
```

### navegar para uma branch branches
```bash
# sendo NAME o nome da sua branch
git checkout NAME
```

### renomear uma branch branch
```bash
# sendo NAME o nome da sua branch
git branch -m NAME
```

### merjar branch
```bash
# sendo NAME o nome da branch que vc quer merjar
git merge NAME
```
