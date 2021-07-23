# <div align="center"> Git Branches  :memo:  </div>
<div align="center"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/tayhsn/git-branchs?logoColor=black&style=social"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/tayhsn/git-branchs?logoColor=green&style=social"> </div>

### Comandos para utilizar branches no Git :octocat:

Você pode copiar esse repositório para o seu perfil com FORK ou salvá-lo com uma STAR. ✨

<hr>

Branches são ramificações, ou seja, extensões da main em que você pode trabalhar em novas funcionalidades sem impactar a branch principal. Uma vez que você finaliza a funcionalidade e garante sua eficiência, é só juntar as duas branches.

Essa é uma forma de ganhar produtividade no desenvolvimento de projetos maiores, e essencial em projetos colaborativos.

<hr>

### Criando uma branch

* Cria uma nova branch

  ``` git branch novaBranch```

* Muda para a branch criada

  ``` git switch novaBranch ``` || ```git checkout novaBranch```

  OU 

* Cria a branch e move pra ela ao mesmo tempo

  ```git checkout -b novaBranch```

<hr>

### Listando as branches


* Lista as branches locais

  ``` git branch ```

* Lista as branches remotas

  ``` 	git branch -r```

* Lista todas as branches locais e remotas

  ``` 	git branch -a```

<hr>

### Trabalhando na branch

* Trazendo as alterações do repositório remoto para o local (incluindo outras branches)

  ```git pull```

* Commita na branch

  ```git commit -m "mensagem"```

* Empurra as alterações

  ``` git push origin Branch ```

* Também é possivel renomear a branch 

  ```git branch -m novoNome```

<hr>
### Juntando as branches

* Fazendo o MERGE entre as branch da funcionalidade e a branch principal

  ``` git merge outraBranch ```

  > Esse comando junta outra branch na que você está. Muito cuidado, pois você precisa estar na branch que deseja trazer as alterações.
  >
  > Para confirmar em que branch está use o comando ```git branch```

<hr>
### Deletando uma branch

* Deletando uma branch local

  ``` git branch -d Branch ```

* Deletando uma branch remota

``` git push origin -delete Branch ```

<hr>
Documentação oficial: https://git-scm.com/docs

Git Command Explorer: https://gitexplorer.com/
