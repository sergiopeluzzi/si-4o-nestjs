# Aula 01
## Instalação NestJS

### Instalar as depedencias de ambiente para o Nest

  * Node: https://nodejs.org/
  * Git: https://git-scm.com/downloads

### Verifique se as instalações estão corretas com os comandos:

`node -v`
`npm -v`
`git --version`

### Instale o Nestjs cli globalmente com o NPM

`npm i -g @nestjs/cli`

### Crie um novo projeto Nestjs com o cli instalado

`nest new project-name` substitui project-name pelo nome do seu projeto. Lembrando que faremos uma api rest com o Nest

### Acessando e configurando

Acesse a pasta do projeto com `cd project-name` e rode o comando para iniciar o Nest em modo de desenvolvimento com o comando `npm run start:dev`.

Você pode acessar e ver a aplicação rodando em http://localhost:3000

Vamos configurar nossas variaveis de ambiente e precisamos instalar o config do Nestjs com o comando `npm i --save @nestjs/config`, isso fará com que o **@nest/config** seja instalado como dependencia do projeto

Vamos configurar também nosso banco de dados e aqui teremos duas opções: **mysql** ou **mongodb**. Para **mysql** use o comando `npm install --save @nestjs/typeorm typeorm mysql2` para instalar o typeorm e o mysql no seu projeto. Já para o **mongodb**, utilize  o comando `npm i @nestjs/mongoose mongoose` para instalar o mongoose no seu projeto. *Obs: Essas instalações são apenas dos __drivers__ para comunicação com o banco de dados. Caso você utilize o mysql, precisará de um servidor do mysql rodando na sua máquina, mesmo vale para o mongodb. Você consegue gratuitamente fazendo o download pelo site: https://dev.mysql.com/downloads/mysql/ ou https://www.mongodb.com/try/download/community*
