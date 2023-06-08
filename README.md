# GIT 



Queremos que um repositório do Git seja inicializado, e para tal usamos o comando `git init`.

Comandos:

```perl
git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"
```

=> Informar quem é você para que ele armazene corretamente os dados do autor de cada uma das alterações no código.

`cd ` => Se mover entre pastas.

`git init`=>Iniciar um repositório no Git.

`git status`=>Mostrar o estado do repositório.

`git add <file>` =>Adicionar as modificações de um arquivo a serem enviadas pelo commit.

`git add .` => Começar a monitor todos os arquivos da pasta.

`git commit -m "Escrever aqui a mensagem"` => Salvar as alterações + Mensagem descritiva da modificação.

 `git log`=>Verificar o histórico de alterações.

`git log --oneline`=>Verificar o histórico de alterações resumidas em uma linha.

`git log -p`=>Verificar o histórico de alterações detalhadas.

http://devhints.io/git-log => Formatos que podemos usar como filtros para mostrar nosso histórico

**commit**: *check point* para indicar que houve mudança, junto de uma mensagem.

- `HEAD`: Estado atual do nosso código, ou seja, onde o Git os colocou
- `Working tree`: Local onde os arquivos realmente estão sendo armazenados e editados
- `index`: Local onde o Git armazena o que será *commitado* (o local entre a *working tree* e o repositório Git em si).

**Repositório Remoto**:um servidor local para onde possamos enviar nossas alterações, que ficarão acessíveis para outras pessoas

`mkdir NomePasta `=>Criar uma pasta

`git remote add nome-repositorio caminho/para/o/repositorio`=> Criar um "link" do nosso repositório local com o repositório remoto.

`git init --bare`=>Com este comando nós criamos um repositório que não terá a *working tree*, ou seja, não conterá uma cópia dos nossos arquivos. Como o repositório servirá apenas como servidor, para que outros membros da equipe sincronizem seus trabalhos, poupamos espaço de armazenamento desta forma.

`git push [repositorio] master` =>Enviar as alterações para o repositório remoto ao alterar os códigos em nosso repositório local

`git pull NomeServidor master` =>Trazer os dados modificados

