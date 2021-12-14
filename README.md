# Plantaat
Projeto pessoal de planta de pontos de energia.

## Necessário

 - [Node Js](https://nodejs.org/en/download/)
 - [SQL Server Management Studio](https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15)
 - [SQL Server Configuration Manager](https://docs.microsoft.com/pt-br/sql/relational-databases/sql-server-configuration-manager?view=sql-server-ver15)

## Intalação
### Dev mode

 - Na pasta /Back (instalar dependencias do Back).
 ``` npm install ```
 
 - Na pasta /Front (instalar dependencias do Front).
 ``` npm install ```
 
### Prd mode

 - Na pasta /Back (instalar dependencias do Back).
 ``` npm install ```
 
 - Na pasta /Front (instalar dependencias do Back).
 ``` npm install ```
 
 - Na pasta /Front (Buildar o Front).
 ``` ng build ```
 
 - Inserir Build da pasta '/dist' na pasta '/webapps' no apache;
 
 - Configurações do Tomcat [link](https://examples.javacodegeeks.com/enterprise-java/tomcat/apache-tomcat-rewrite-rules-example/).

## Run
### Dev mode

 - Na pasta /Back (instalar dependencias do Back).
 ``` npm server ```
 
 - Na pasta /Front (instalar dependencias do Front).
 ``` ng serve -o ```
 
 ### Prd mode

 - Na pasta /Back (instalar dependencias do Back).
 ``` npm server ```
 
 - Executar arquivo 'startup' no arquivo '... \apache-tomcat-8.5.72\bin'.

## Detalhes de configuração 
### Arquivos de configuração Back

 - app-config.js

### Arquivos de configuração Front

 - environments/environment.prod.ts
 - environments/environment.ts
 
 
