# Curso Git e Github teomewhy 2025
Instructor: Teo Calvo - @teomewhy <br>
Onde ver as aulas: Na twitch (https://twitch.tv/teomewhy) ou no Canal dele do Youtube (https://youtube.com/@teomewhy) <br>

<p> Um curso para inciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub. <br>

Além disso, vamos trabalhar com GitFlow ao final do curos e Visual Studio Code. <br>

Confira tudo o que temos no Youtube acima ou na Twitch. É Gratis! Segue o Link:

[Curso Git 2025](https://youtube.com/@teomewhy)

Além no nosso YouTube, se ligue no nosso site e agenda para ficar por dentro de tudo que vai rolar em 2025.

[teomewhy.org](https://teomewhy.org;schedule)

</p>

## Dia 01 - Instalando o Git, Comandos Bash

### Instalação
</p> A instalação do git está disponível na url (https://git-scm.com/downloads) </p>
<p>Plataformas disponíveis: </p>
* Windows
* Linux/Unix
* MacOS

<p>Literalmente é um Próximo > Próximo > Instalar > Concluido. Fica a atenção somente na conveção de alterar a branch que <br> 
no padrão do aplicativo vem como *master*, alterar para *main*
</p>

### Comandos Bash
* ls -> lista arquivos
* cd -> move entre diretorios
* pwd -> mostra diretorio de trabalho
* cat -> exibe conteudo do arquivo
* rm -> remove arquivo ou diretorio

## Dia 02

Vendo como podemos atuar no Projeto com mais de uma branch (Ponteiro ou executor para um específico ponto do Projeto). <br> 
A Prática é que a main não seja utilizado no processo. <br>
Com isso, cria-se outras para que os desenvolvedores possam atuar em um mesmo projeto.

### Comandos Git

git init .                      -> Cria um repo git na pasta atual <br>
git status                      -> Mostra o status do trabalho (de cada arquivo) <br>
git add nome_arquivo            -> Adiciona arquivo para ser commitado <br>
git commit - m "msg"            -> Faz commit do que estava para ser commitado <br>
git log                         -> Mostra todo o histórico de commit <br>
git diff <nome_arquivo>         -> Demonstra o log de mudanças do arquivo em questão. <br>
git checkout -b <nome_branch>   -> Cria uma nova branch para o projeto <br>
git branch                      -> Lista as branchs existentes <br>
git checkout <nome_brach>       -> Modifica a Branch que está em utilização no momento. <br>
git fetch                       -> Comando que permite baixar conteúdos de um repositório remoto para o repositório local

## Dia 03
<p>Github. Controlador de Respositorios em nuvem dos Projetos criados em git.<br>
Semelhantes a ele no mercado existem outros como: gitlab, bitbucket, Azure devops etc <br>
Se não tiver uma conta, basta entrar no [github.com](github.com) e com um e-mail criar sua conta grátis. </p>

Em Repositorios, basta criar um novo<br>
Em seguida, faremos a ação solicitada para que façamos a ação de levar o repositorio trabalhado nos outros dias, para o ambiente do github.<br>

Logo, os comandos abaixo, serão usados no bash:
```
git remote add origin https://github.com/seuusuario/NomeDiretorio.git
git branch -M main
git push -u origin main
```
## Fluxo de trabalho Git local
01. git checkout -b <nova_branch>
02. cria ou atualiza arquivos
03. git status
04. git add *arquivos*
05. git status
06. git commit -m "minha mensagem"
07. git checkout main
08. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add *arquivos* 
06. git status
07. git commit -m "nova mensagem"
08. git push oring <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -d <nova_branch>


## Fluxo de trabalho GitHub <> Local (projetos open-source)

01. Fork do projeto para o seu próprio GitHub
02. git clone <endereco do projeto fork>
03. git checkout -b <nova_branch>
04. alterações de arquivos
05. git status
06. git add *arquivos* 
07. git status
08. git commit -m "nova mensagem"
09. git push oring <nova_branch>
10. abrir Pull request no GitHub da branch fork para main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -d <nova_branch>

### Observações
Em caso de erro ao tentar o comando `git push origin <nome_branch>` utilize o o comando:
`git remote set-url origin git@github.com:seu_username/nome_repositorio.git` (onde seu_username é o seu login e nome_repositorio é o repositório do seu GitHub)

## Pessoas Participantes
- Gustavo Lourenço
- Teo Calvo

## Dia 04

### Git Flow
Trabalhar com **develop**
checout a partir da **develop**
pull-request para **develop**
release para **main**

#### Convention Commit ####
[Medium](https://miro.medium.com/v2/resize:fit:720/format:webp/1*izVKF4AT1iDtv4fJO8oWWA.png)

#### Paterns names of branches
[Medium](https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106)

