# <div align="center"> GIT Branches  :memo:  </div>
<div align="center"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/tayhsn/git-branchs?logoColor=black&style=social"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/tayhsn/git-branchs?logoColor=green&style=social"> </div>

### Comandos de ramificação (branches) no GIT :octocat:

 Para facilitar, faça um FORK para copiar o repositório ou deixe uma STAR para salva-ló. ✨

<hr>

* Para ver em qual branch você esta no momento

``` GIT STATUS ```

* Para trazer todas as branches do repositorio remoto

```GIT PULL ```

<hr>

* Listar todas as branchs locais

``` GIT BRANCH ```

* Listar todas as branchs remotas

``` GIT BRANCH -R```

* Listar todas as branchs locais e remotas

``` GIT BRANCH -A```

<hr>

* Cria uma nova branch

``` GIT BRANCH <nome-branch>```

* Muda para a branch criada

``` GIT SWITCH <nome-branch> ```

OU 

* Cria uma nova branch e muda pra ela ao mesmo tempo

``` GIT CHECKOUT -B <nome-branch> ```

<hr>

* Empurrar seus arquivos para a branch local

``` GIT PUSH -U ORIGIN <nomeBranch> ```

* Se a branch ja foi versionada, basta 

``` GIT PUSH ```

<hr>

* Fazendo o merge de outra branch para a branch atual (ou seja, juntar a branch que você terminou de trabalhar com a branch principal)

``` GIT CHECKOUT MAIN ``` { garantindo que está indo para a branch principal que vai receber as alterações } 

``` GIT MERGE <outra-branch> ```

<hr>

* Deletando uma branch local

``` GIT BRANCH -D <nome-branch> ```

* Deletando uma branch remota

``` GIT PUSH ORIGIN -DELETE <nome-branch> ```

<hr>

* Para alternar entre as branch pode utilizar tanto SWITCH quanto CHECKOUT 

Para mais comandos: https://comandosgit.github.io/
