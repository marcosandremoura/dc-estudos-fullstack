
==================================================
ANOTAÇÕES ESTUDO DESENVOLVIMENTO FULLSTACK
--------------------------------------------------             
HTML / CSS / JS / REACT / NODE / GIT/GITHUB / SQL
==================================================





DICAS E INFORMAÇÕES INTERESSANTES
=================================


PROJETOS COM HTML E CSS
-----------------------
Landing Pages / Blogs / Catálogos / Portifólios / E-mail Marketing / Telas de Dashboards
Criação de Desenhos Web / Efeitos Web / Animações Web



CHECAR ERROS NO HTML
--------------------
O Markup Validation Service é um validador do World Wide Web Consortium que permite que os usuários da Internet verifiquem documentos HTML e XHTML pré-HTML5 para marcação bem formada em relação a uma definição de tipo de documento.
https://validator.w3.org/#validate_by_input



CAN I USE
---------
Fornece a relação atualizada de quais os navegadores e as suas versões, que suportam as devidas 
tecnologias web front-end.
https://caniuse.com/




CODEPEN
-------
O CodePen é um site que oferece um ambiente onde a medida que você vai escrevendo seu código, 
já vai vendo os resultados da construção.
Ótimo para linguagens front-end como HTML, CSS, JavaScript.
https://codepen.io/




STACK BLITZ
-----------
O Stackblitz é um site que oferece uma experiências de desenvolvimento instantâneas. É ambiente online, 
onde a medida que você vai escrevendo seu código, já vai vendo os resultados da construção.
Ótimo para linguagens front-end e backend como React e Node.js.
https://stackblitz.com/




WHIMSICAL
---------
Site para criar Mockup/Wireframe

























==============
 ESTUDOS HTML
==============


COMANDOS E ATALHOS NO HTML
--------------------------
fazer comentário __________________________________________________ <ctrl k + ctrl c>  (ou)  <Ctrl;>  (ou)  <!-- -->
copiar linha atual nas linhas acima _______________________________ <cursor na linha desejada / alt + shift + seta cima>
copiar linha atual nas linhas abaixo ______________________________ <cursor na linha desejada / alt + shift + seta baixo>
fazer parte do código/projeto com um atalho _______________________ div.container>ul#lista>li*10
























=============
 ESTUDOS CSS
=============


h1{
    color: red;
}
SELETOR(h1) - PROPRIEDADE(color) - VALOR(red)



COMANDOS E ATALHOS NO CSS
-------------------------
fazer comentário (1 linha) _________________________________________ // 
fazer comentário (várias linhas) ___________________________________ <ctrl k + ctrl c>  (ou)  /* */  
copiar linha atual nas linhas acima _______________________________ <cursor na linha desejada / alt + shift + seta cima>
copiar linha atual nas linhas abaixo ______________________________ <cursor na linha desejada / alt + shift + seta baixo>



TREINAR CSS
-----------

CSS TRICKS
O CSS Tricks é uma documentação que demonstra os truques e comandos do CSS.
https://css-tricks.com/snippets/css/a-guide-to-flexbox/


CSS BATTLE
O CSSBattle é um jogo online de golfe com código CSS . Aqui, jogadores de todo o mundo tentam replicar visualmente "Alvos" no menor código CSS possível e batalham para chegar ao topo da tabela de classificação.
https://cssbattle.dev/


FLEXBOX
O Flexbox é um modelo de layout do CSS que permite a melhor distribuição dos elementos na página.
Ele facilita na criação de interfaces que sejam responsivas.     
Site para treinar o FLEXBOX.
https://flexboxfroggy.com/


MEDIA QUERY (Aprender sobre adequação desktop/mobile)
Media query, nada mais é do que uma estrutura do CSS que permite aplicar estilizações, 
fazendo com que esta página possa se adequar ao layout em diferentes tamanhos de tela e tipos de mídia.
https://www.w3schools.com/css/css_rwd_mediaqueries.asp
https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries



























=============
 ESTUDOS GIT
=============


TREINAR GIT
-----------
https://git-school.github.io/visualizing-git/
Gitflow (modelos mapa branchs)
Gitlabflow (modelos mapa branchs)




COMANDOS GIT (TERMINAL IOS)
------------------------------------------
limpar a linha atual do terminal ___________________________________ command l
deixar o cursor do terminal em cima ________________________________ clear
limpar todo o terminal _____________________________________________ option command l


COMANDOS GIT (GIT BASH WINDOWS)
------------------------------------------

Como sair do git status (vin)? Para sair do modo de edição, digite:
01 - control c
02 - :wq (para salvar alterações e sair)  OU  :q (para sair sem salvar alterações)  
03 - ENTER

iniciar controle versionamento na pasta/projeto em questão _________ git init
listar o que tem na pasta em questão _______________________________ ls (list directory contents)
listar o que tem na pasta em questão incluindo ocultas _____________ ls -a  (ou)  ls -la
listar o que tem em uma pasta específica ___________________________ ls <caminho-da-pasta>
criar uma pasta ou outra dentro da pasta em questão ________________ mkdir <nome-da-pasta>
ir para a pasta informada __________________________________________ cd <nome-da-pasta> (change diretory)
ir para uma pasta anterior _________________________________________ cd ..
criar um arquivo na pasta em questão _______________________________ touch <nome-do-arquivo>
abrir a pasta em questão no vs code ________________________________ code .
exibir o path atual ________________________________________________ pwd
configurar nome do usuario _________________________________________ git config --global user.name "<nome-do-usuário>"
configurar email do usuario ________________________________________ git config --global user.email "<email-do-usuário>"
confirmar nome do usuario __________________________________________ git config --global user.name
confirmar email do usuario _________________________________________ git config --global user.email
mudar da branch "master" para a branch "main" ______________________ git branch -M "main"
criar branch _______________________________________________________ git branch "<nome-da-branch>"
listar as branchs do repositório e indicar a que você está _________ git branch
excluir a branch mencionada ________________________________________ git branch -d <nome-da-branch>
excluir forçadamente a branch mencionada ___________________________ git branch -d <nome-da-branch>
renomear a branch atual ____________________________________________ git branch -m <novo-nome-da-branch>
renomear uma branch ________________________________________________ git branch -m <nome-antigo> <nome-novo>
listar todas as branchs remotas ____________________________________ git branch -a
mudar para branch desejada _________________________________________ git checkout <nome-da-branch>
criar branch e ja mudar para ela ___________________________________ git checkout -b "<nome-da-branch>"
criar branch dentro de uma branch específica _______________________ git checkout -b "<nome-da-branch>" "<branch-específica>"
exibir alterações do projeto, status da stage area _________________ git status
adicionar arquivos/alterações na stage area, antes do commit _______ git add <nome-do-arquivo/alteração>
adicionar arquivos/alterações na stage area, antes do commit _______ git add . (add todos os arquivos/alterações da pasta)
mostrar histórico dos commits da branch atual e da main ____________ git log 
mostrar diferenças realizadas no projeto após o último commit ______ git diff (diferença) 
registrar na stage area, as alteraçÕes feita no projeto ____________ git commit -m "<texto-informando-as-alterações>" 
alterar a mensagem do commit _______________________________________ git commit --amend
descartar as alterações feitas no arquivo após o ultimo commit _____ git restore <nome-do-arquivo>
descartar as alterações feitas no projeto após o ultimo commit _____ git restore .
conectar o repositório local com o GitHub __________________________ git remote add origin <link-repositório-github>
empurrar commits do repositório local para o remoto ________________ git push origin <noma-da-branch>
puxar os commits do repositório remoto para o local ________________ git pull (traz atualizações e mostra conflitos)
fazer clone/cópia de um repositório remoto para um local ___________ git clone
trazer as alterações feitas em uma branch para a que você está _____ git merge <nome-da-branch-que-voce-quer-trazer>
concluir uma mesclagem que foi interrompida ________________________ git merge --continue
cancelar o merge que foi dado ______________________________________ git merge --abort

deixar o cursor do terminal em cima ________________________________ ctrl l 
limpa o terminal ___________________________________________________ clear
copiar _____________________________________________________________ ctrl insert
colar ______________________________________________________________ shift insert
sair do vin ________________________________________________________ control c / :wq ou :q / ENTER

No entanto, se você já subiu este branch para o repositório, terá que remover o antigo e então subir o novo, 
após ter renomeado com o comando acima. Para isso faça
git push origin --delete <nome-antigo>
git push origin <nome-novo>





PROCESSO DE PUSH QUANDO FICA DANDO ERRO
---------------------------------------
01 - { git push origin <nome-da-branch> 
02 - { git pull (para trazer as atualizações e mostrar os conflitos)
03 - resolve os conflitos, 
04 - { git add <nome-do-arquivo>, 
05 - { git merge --continue, 
06 - { git push




CHAMADA COM GIT
---------------
cd <nome-pasta-base>/
cd <nome-pasta-seguinte>/
cd <nome-pasta-do-repositório>/
git clone <url-do-repositório>
ls
cd <nome-do-repositório>
code .
git add <nome-do-arquivo-no-vscode> ou git add . (adiciona todos os arquivos da pasta em questão)
git commit -m <texto-informando-a-alteração-realizada>
git push, 
(Se der erro)
git pull - para trazer as atualizações e mostrar os conflitos   
Resolve os conflitos, 
git add <nome-do-arquivo-no-vscode> ou git add . (adiciona todos os arquivos da pasta em questão)
git merge --continue, 
(vin) control c / :q
git push

























====================
 ESTUDOS JAVASCRIPT
====================


VARIÁVEIS 
---------
[LET]  
[VAR]
[CONST]

DADOS
-----
[STRING]
[NUMBER]
    -OPERADORES (SIMBOLOS COM FUNÇÕES)
        ( + )   ( - )   ( * )   ( / )
    -OPERADORES DE COMPARAÇÃO (SIMBOLOS COM FUNÇÃO)
        ( == )   ( != )   ( < )   ( > )   ( <= )   ( >= )
    -OPERADORES LÓGICOS
[BOOLEAN]
    -TRUE
    -FALSE
 



COMANDOS JAVASCRIPT
-------------------
identificar o tipo de vairável __________________________________________ TYPEOF




CODEPEN
-------
O CodePen é um site que oferece um ambiente onde a medida que você vai escrevendo seu código, 
já vai vendo os resultados da construção.
Ótimo para linguagens front-end como HTML, CSS, JavaScript.
https://codepen.io/

























=============
 ESTUDOS DOM
=============

Document Object Model
(Modelo de Objeto de Documentos)

É uma interface de programação para documentos HTML, XML e SVG . 
Ele fornece uma representação estruturada do documento tipo uma árvore geneológica. 
O DOM define métodos que permitem acesso à árvore, para que eles possam alterar a estrutura, 
estilo e conteúdo do documento.
É utilizado pelo navegador Web para representar a sua página Web. Quando altera-se esse modelo com 
o uso do Javascript, altera-se também a página Web. 
É muito mais fácil trabalhar com DOM do que diretamente com código HTML ou CSS.

 
// Pegando o HTML
const HTML = document.firstElementChild;

// Pegando o HEAD
const HEAD = HTML.firstElementChild

// Pegando o BODY
const BODY = HTML.lastElementChild

// Pegando o <main>
const MAIN = BODY.firstElementChild

// Pegando o <header>
const HEADER = MAIN.firstElementChild

// Pegando o <h1>
const H1 = HEADER.firstElementChild

// Pegando de forma mais rápido as imagens
const imagem = document.getElementById("imagem");

// Alterando o SRC da imagem
imagem.src = "https://revistacarro.com.br/wp-content/uploads/2022/06/Icona_5.jpg";

// Auterando o style da imagem
imagem.style.width = "20em";

























===============
 ESTUDOS REACT
===============


STACK BLITZ
-----------
O Stackblitz é um site que oferece uma experiências de desenvolvimento instantâneas. É ambiente online, 
onde a medida que você vai escrevendo seu código, já vai vendo os resultados da construção.
Ótimo para linguagens front-end e backend como React e Node.js.
https://stackblitz.com/

























===============
 ESTUDOS NODE
===============


STACK BLITZ
-----------
O Stackblitz é um site que oferece uma experiências de desenvolvimento instantâneas. É ambiente online, 
onde a medida que você vai escrevendo seu código, já vai vendo os resultados da construção.
Ótimo para linguagens front-end e backend como React e Node.js.
https://stackblitz.com/




















.



