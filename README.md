# Curso Git e Github teomewhy 2025
Instructor: Teo Calvo - @teomewhy <br>
Onde ver as aulas: Na twitch (https://twitch.tv/teomewhy) ou no Canal dele do Youtube (https://youtube.com/teomewhy) <br>

<p> Um curso para inciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub. <br>
Além disso, vamos trabalhar com GitFlow ao final do curos e Visual Studio Code. <br>
Confira tudo o que temos no Youtube acima ou na Twitch. É Gratis! 
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
git checkout <nome_brach>       -> Modifica a Branch que está em utilização no momento.

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
## Pessoas Participantes
Teo