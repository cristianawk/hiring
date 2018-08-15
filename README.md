# FluxoTI: trabalhe conosco

Olá desenvolvedor, quer trabalhar conosco? Basta dar um *fork* nesse repositório, fazer o nosso teste e abrir um PR com a sua implementação.  
Também precisamos que envie seu curriculo para a gente, no email dev@fluxoti.com. Pode mandar tudo que achar interessante junto: linkedin, twitter, blog, site, github, projetos open-source que participa, artigos que tenha escrito, enfim, tudo mesmo que julgar interessante.

## Requisitos

- PHP
- Framework Laravel
- JS
- HTML5
- SASS
- CSS3
- Gostar de programar (mas gostar muito mesmo)
- Saber trabalhar com Linux
- Saber trabalhar com GIT
- Gostar de desafios

---
Utilizando o framework Laravel, crie uma aplicação que consulte a API do [HackerNews](https://github.com/HackerNews/API). Você fica livre para decidir o que deseja exibir e como deseja exibir, se vai utilizar cache ou não, etc. Deixamos isso ao seu critério. Você pode apresentar as informações que julgar mais importantes ou interessantes e no layout que achar mais bonito e funcional :wink:.  
O *README* do projeto deverá conter as informações sobre como instalar e executar a aplicação.

### Alguns diferenciais

- Utilizar Vue.js na implementação
- Utilizar Vuex na implementação
- Utilizar um pré-processador CSS (usamos SASS aqui, mas não tem problema ser outro não :smile:)
- Utilizar ES6 (amamos ES6 :heart_eyes:)
- Utilizar Docker / Docker Compose

### Configurando o Projeto com VueJs

 Bom, vou usar uma aplicação básica com Vue.

### Instalando o Vue Cli

$ yarn global add vue-cli
#ou
$ npm install -g vue-cli

#eu prefiro usar npm, apesar de dizerem que yarn é mais rápido e tende a resolver conflitos de versão e tem cache local mas...

$ vue -V
2.9.3
#essa é a minha versão usada


### Criando o Projeto

 Uma vez que já tenho o basico instalado vamos ao restante:

 $ mkdir hackernews
 $ cd hacersnews
 $ vue init webpack

 Ai vem uma série de perguntas de como configurar o projeto que não vou detalhar aqui :p

 e já nesse ponto já da para ter o projeto 'cru' rodando

 $ npm run dev

#navegando em http://localhost:8080

### Segundo passo: Trabando com componentes HacerNews
 Bom o primeiro que noto quando abro o HackerNews é a iônica barra de navegação laranja.
 Então vou usar esse componente como exemplo 'Navbar' em /src/components/

### Registrando o Componente Navbar
 Para isso tenho que importa-lo em /src/App.vue 

#nesse momento ja tenho o projeto rodando com o componente Navbar

*OBS:* Mesmo utilizando javascript para exibir os dados, é necessário que a API do github seja consumida pelo PHP. Num projeto real, isso não seria necessário, mas precisamos ver algum código backend :wink:
