## Comandos do git


## iniciar o git na aplicação
```bash
git init
```

## Colocar diretório em que seu repositório está armazenado.
```bash
git remote add origin <URL do repositorio: https://github.com/pl4kill/Use.Git..git>
```

#### Clonar repositório github
```bash
git clone <URL do repositorio: https://github.com/pl4kill/Use.Git..git>
```

#### Verificar o que foi alterado
```bash
git status
```

#### Adicionar alteraçoes na staging area
```bash
# "." podendo ser tbm o nome do arquivo
git add . 
```

#### Salvar alterações
```bash
## MSG sendo sua mensagem
git commit -m "MSG"
```

#### Enviar os commits de sua branch e repositório Git local para o seu repositório remoto.
```bash
## MSG sendo sua mensagem
git push -u origin master
```

#### Listar branches
```bash
git branch
```

#### Criar uma branch
```bash
# sendo NAME o que nome que quero para minha branch
git checkout -b NAME
```

#### Navegar para uma branch branches
```bash
# sendo NAME o nome da sua branch
git checkout NAME
```

#### Renomear uma branch branch
```bash
# sendo NAME o nome da sua branch
git branch -m NAME
```

#### Merjar branch
```bash
# sendo NAME o nome da branch que vc quer merjar
git merge NAME
```
