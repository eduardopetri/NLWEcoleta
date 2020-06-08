![Ecoleta Logo](https://github.com/eduardopetri/NLWEcoleta/blob/master/Ecoletaimage.png)
#
<p align="center">
  <a href="##-Projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-globe_with_meridians-API-Externa">API Externa</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Como-utilizar:">Como Utilizar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Contribuição">Como contribuir</a>
</p>


## :triangular_ruler: Projeto
### Ecoleta é um projeto que foi desenvolvido durante a "Next Level Week 01" da Rocketseat, que tem como base a semana internacional do meio  ambiente. O objetivo da aplicação é conectar pessoas à empresas que coletam resíduos orgânicos e recicláveis.
<h1 align="center">
    <img alt="Ecoleta image mockup" title="Ecoleta" src="https://github.com/eduardopetri/NLWEcoleta/blob/master/EcoletaMockup.png" width="400px" />
</h1>

## :computer: Tecnologias
### Este projeto foi desenvolvido com as seguintes tecnologias:
* TypeScript
* Node.js
* React
* React Native
* SQLite

## :globe_with_meridians: API Externa
#### Para buscar os estados e cidades do Brasil foi utilizado a API do IBGE que pode ser encontrada [aqui](https://servicodados.ibge.gov.br/api/docs/localidades).

## :grey_question: Como utilizar:
#### Você pode clonar esse repositório utilizando [GIT](https://git-scm.com/) e digitando o seguinte comando no terminal: 
> `$ git clone https://github.com/eduardopetri/NLWEcoleta`

#### Para baixar e gerenciar os pacotes é necessário que você tenha o [Node.js](https://nodejs.org/en/) instalado na sua máquina recomendo que instale a partir do gerenciador de pacotes [Chocolatey](https://chocolatey.org/)
### :globe_with_meridians: Backend
#### Após a instalação do node vá para o diretório da pasta server
> `$ cd NLWEcoleta/server`

#### Instale as dependências:
> `$ npm install`

#### Rode as migrations
> `$ npm knex:migrate`

#### Rode as seeds
> `$ npm knex:seed`

#### Inicie o servidor
> `$ npm run dev`

### :computer: Frontend

#### Vá para a pasta web
> `$ cd NLWEcoleta/web`

#### Instale as dependências
> `$ npm install`

#### Inicie a aplicação
> `$ npm start`

### :iphone: Mobile
#### Para utilizar o app mobile é necessário ter o [expo](https://expo.io/) instalado no seu computador e smartphone.

#### Vá para a pasta mobile
> `$ cd NLWEcoleta/mobile`

#### Instale as dependências
> `$ expo install`

#### Inicie a aplicação
> `$ expo start`

## :bulb: Contribuição
#### Você pode contribuir da forma que quiser, basta fazer um fork da aplicação e criar um pull request para a aprovação da sua contribuição. 

##
Você pode me encontrar no [Linkedin](https://www.linkedin.com/in/eduardo-petri/) para conversarmos sobre a aplicação ou alguma ideia nova. __Let's code :coffee: :computer: !__
