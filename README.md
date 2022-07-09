# DS Delivery 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/moisesguilherme/dsdeliver-sds2/blob/main/LICENSE) 

# Sobre o projeto

https://dsdeliveryweb.netlify.app/

DS Delivery é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema de pedido e entrega de restaurante. Os dados da solicitação do pedido são coletados via web e posteriormente os pedidos são entregues e confirmados no app mobile.

(https://github.com/moisesguilherme/assets/blob/main/sds2-dsdeliver/ws-dsdeliver.gif)

## Layout web
![Web 1](https://github.com/moisesguilherme/assets/blob/main/sds2-dsdeliver/web_01.png)

![Web 2](https://github.com/moisesguilherme/assets/blob/main/sds2-dsdeliver/web_02.png)

![Web 3](https://github.com/moisesguilherme/assets/blob/main/sds2-dsdeliver/web_03.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/moisesguilherme/assets/blob/main/sds2-dsdeliver/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## API
- Mapbox
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/moisesguilherme/dsdeliver-sds2.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/moisesguilherme/dsdeliver-sds2.git

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

## Front end mobile
Pré-requisitos: npm / expo

```bash
# clonar repositório
git clone https://github.com/moisesguilherme/dsdeliver-sds2.git

# entrar na pasta do projeto front end web
cd front-mobile

# instalar dependências
expo install 

# executar o projeto
npm start
```

# Autor

[Moisés Guilherme](https://www.linkedin.com/in/moises-guilherme/ "Perfil Linkedin Moisés Guilherme")
