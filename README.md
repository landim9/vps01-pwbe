# Avaliação somativa PWBE

## Objetivo:
O objetivo é praticar o desenvolvimento de operações CRUD, além de implementar funcionalidades adicionais conforme requisitos específicos.

## Utilidades:
- API - Criação de API (Plataforma de Interface de Aplicação)

- CRUD - Funcionalidades de criar, ler, atualizar e excluir

- MVC - Padrão de projeto (Modelo, Visão e Controle)

- Testes - Testes unitários da API utilizando software Insomnia

|Tecnologias|Descrição|
|-|-|
|<img src="https://w7.pngwing.com/pngs/717/111/png-transparent-mysql-round-logo-tech-companies-thumbnail.png" style="width:50px;">[XAMPP - MySQL MariaDB](https://www.apachefriends.org/pt_br/index.html)|Banco de dados relacional|
|<img src="https://static-00.iconduck.com/assets.00/node-js-icon-454x512-nztofx17.png" style="width:50px;">[NodeJS](https://nodejs.org/en)|Framework para construção de APIs|
|<img src="https://logowik.com/content/uploads/images/visual-studio-code7642.jpg" style="width:50px;">[VsCode](https://code.visualstudio.com/)|IDE|
|<img src="https://seeklogo.com/images/I/insomnia-logo-A35E09EB19-seeklogo.com.png" style="width:50px;"> [Insomnia](https://insomnia.rest/)|Ferramenta para testes unitários|

## Funcionalidades a serem desenvolvidas:
- CRUD de Clientes
- CRUD de Veiculos
- CRUD de Telefones
- CRUD de Alugueis

## Como testar esta API
Necessário ter o ambiente/tecnologias acima instaladas
- 1 Clonar este repositório
- 2 Abrir com VsCode
- 3 Instalar o banco de dados
    - A Abrir o XAMPP e clicar em start no MySQL, ou iniciar o MySQL da maneira que preferir.
    - B Rodar os scripts de criação do Banco de dados e de população com dados de teste.
        - ./bcd/script.sql
- 4 Abrir um terminal **cmd** ou **bash** e navegar até a pasta ./api
```bash
cd api
```
- 5 Instalar todas as dependências
```bash
npm init

npm install express cors mysql nodemon

npm i
```
- 6 Executar com nodemon ou node server.js
```bash
nodemon
```
ou
```bash
npx nodemon
```
ou
```bash
node server.js
```
- 7= Abrir o aplicativo **Insomnia** e importar a coleção de rotas de testes que está na pasta ./testes/insomnia.json
- 8 Executar todos os testes
