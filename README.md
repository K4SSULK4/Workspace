# GIT 



Queremos que um repositório do Git seja inicializado, e para tal usamos o comando `git init`.

Comandos:

```perl
git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"
```

=> Informar quem é você para que ele armazene corretamente os dados do autor de cada uma das alterações no código.

`git init`=>Iniciar um repositório no Git.

`git status`=>Mostrar o estado do repositório.

`git add <file>` =>Adicionar as modificações de um arquivo a serem enviadas pelo commit.

`git add .` => Começar a monitor todos os arquivos da pasta.

`git commit -m "Escrever aqui a mensagem"` => Salvar as alterações + Mensagem descritiva da modificação.



**commit**: *check point* para indicar que houve mudança, junto de uma mensagem.

 Salvar as alterações

- `HEAD`: Estado atual do nosso código, ou seja, onde o Git os colocou
- `Working tree`: Local onde os arquivos realmente estão sendo armazenados e editados
- `index`: Local onde o Git armazena o que será *commitado*, ou seja, o local entre a *working tree* e o repositório Git em si.