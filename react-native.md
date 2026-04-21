# Desafio React Native

O objetivo deste desafio é desenvolver um app em **React Native com Expo** contendo **3 abas**:

1. **Lista de Pokémons**
2. **Mapa**
3. **Favoritos**

## Requisitos

### 1. Aba de Lista
A aba de lista deve consumir dados da **PokeAPI**.

Requisitos mínimos:
- listar pokémons consumindo a API
- exibir pelo menos nome e imagem
- permitir busca por nome
- ter algum tipo de filtro
- implementar paginação ou load more
- tratar loading
- tratar erro
- permitir favoritar/desfavoritar um item

API sugerida:
- `https://pokeapi.co/api/v2/pokemon`

### 2. Aba de Mapa
A aba de mapa deve conter:

- exibição de mapa
- obtenção da localização atual do usuário
- criação de pins aleatórios no mapa
- sempre que a tela receber foco, o app deve dar zoom em um pin aleatório

### 3. Aba de Favoritos
A aba de favoritos deve conter:

- listagem dos pokémons favoritados
- possibilidade de remover dos favoritos
- persistência local dos dados

## Requisitos técnicos

- usar **React Native com Expo**
- usar navegação por abas(tabs)
- consumir a **PokeAPI**
- persistir favoritos localmente
- o projeto deve rodar com instruções simples

## Entrega

A entrega deve conter:
- link do repositório no GitHub
- instruções claras para rodar o projeto
- breve explicação das decisões técnicas adotadas

## Observações

- Você pode usar as bibliotecas que preferir
- O foco é uma solução funcional, organizada e bem construída