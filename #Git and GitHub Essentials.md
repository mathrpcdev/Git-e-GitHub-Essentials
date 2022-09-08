                #EM CONSTRUÇÃO

# Git and GitHub Essentials![] (C:\Users\Matheus\OneDrive\Área de Trabalho\git-cover.png)

### Os Três Objetos básicos do Git

<img src="C:\Users\Matheus\OneDrive\Área de Trabalho\git-objects.png" style="zoom:50%;" />



`git init`
Irá inicializar um repositório do git na pasta em questão.

`git add "nome_do_arquivo"` 
O arquivo em questão irá para a camada **Staged** . Ou seja, ele irá para a camada "Pronto para envio". Assim sendo ele estará pronto para receber um **commit**.


`git add .` 
Esse ponto final significa que você estará enviando para o _Stage_ todos os arquivos da pasta, portanto, todos os arquivos da pasta ficarão em **Staged**, pronto para serem "_commitados_".

`git remote` - Listará todos os repositórios remotos que o repositório local reconhece.

`git remote add` _nome do local_ _caminho ao local_

`git remote`

`git remote -v`

`git init --bare`
O uso do _**bare**_ significa que esse repositório Git que está se inicializando não possuirá uma **Working Tree**. Com isso estamos indicando que este repositório é um repositório *puro*. Isso serve para que membros da equipe possam sincronizar os seus trabalhos, pois com o `--bare` o repositório em questão **não conterá as cópias de arquivos** de cada integrante do projeto; **em um repositório 'puro' podemos enxergar apenas as alteraçÕes feitas entre os arquivos**.

`git remote rename` _'nome Atual'_ _'Nome futuro'_

`git pull`

`git commit -m` `"nome da atualização"`

`git push`

`git clone`



** Toda vez que uma alteração for feita dentro da pasta em que o git foi inicializado, o `git status` irá reconhecer. Por exemplo:
Acabei de criar um arquivo .txt ou fiz alguma alteração em algum arquivo na pasta em questão. Mesmo que os arquivos esteja atualizados e salvos dentro de sua pasta, ela está salva com a última modificação feita apenas em SUA máquina, mas nos outros repositórios remotos como o GitHub não estará. **
1. git commit -m "descrição da alteração feita"
2. git push main 
Agora sim a atualização foi feita para nuvem; agora está no repositório remoto do GItHub

**Links Úteis:**

[Guia de formatação de texto em Markdown](https://www.markdownguide.org/)

[Documentação oficial do Git](https://git-scm.com/doc)

Onde eu estudei sobre Git e GitHub?
[Alura](https://www.alura.com.br/) e [Digital Innovation One Inc.](https://dio.me/sign-up?ref=Q6T6QGFVNK)

