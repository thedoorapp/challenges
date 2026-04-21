# Desafio Backend Node.js

O objetivo deste desafio é desenvolver uma API em **Node.js** simulando uma funcionalidade comum de rede social: **likes em posts**.

## Objetivo

Criar uma API que permita:

- listar posts
- consultar um post específico
- registrar likes em um post
- consultar a quantidade de likes de um post
- listar os posts com mais likes

## Cenário

Considere que vários usuários podem curtir o mesmo post ao mesmo tempo.

A solução deve considerar esse cenário e garantir consistência dos dados.

## Requisitos

### Posts
Cada post deve conter pelo menos:

- id
- título
- conteúdo
- quantidade de likes

A API deve permitir:
- listar posts
- consultar post por id

### Likes
A API deve permitir:
- registrar like em um post
- informar qual usuário realizou o like

### Regras

- um mesmo usuário não pode curtir o mesmo post mais de uma vez
- múltiplas requisições simultâneas de like devem ser tratadas corretamente
- a quantidade de likes deve permanecer consistente mesmo sob concorrência

## Fila

A solução deve possuir algum mecanismo de **fila/processamento assíncrono** para tratar os likes.

## Cache

A solução deve possuir algum mecanismo de **cache** para otimizar pelo menos um cenário de leitura, como por exemplo:

- listagem de posts
- consulta de post por id
- ranking dos posts com mais likes

## Documentação

A API deve possuir documentação em **Swagger**

## Persistência

Os dados principais podem ser armazenados em:

- arquivo `.json`
ou
- banco de dados **PostgreSQL**

## Requisitos técnicos

- usar **Node.js**
- pode ser utilizado **JavaScript ou TypeScript**
- o projeto deve conter instruções claras para execução
- o projeto deve conter um `README.md`

## Entrega

A entrega deve conter:

- link do repositório no GitHub
- instruções para rodar o projeto
- documentação da API
- breve explicação das decisões técnicas adotadas

## Observações

- a escolha de bibliotecas, arquitetura, fila e cache fica a seu critério
- o foco é uma solução funcional, organizada e bem construída