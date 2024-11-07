---

# Bolo de Cenoura com Cobertura de Chocolate

Este projeto é uma página web simples para apresentar a receita de um bolo de cenoura com cobertura de chocolate. O layout utiliza HTML e CSS para organizar e estilizar os elementos da página, incluindo texto, imagens e a estrutura geral. Abaixo, você encontrará uma explicação detalhada de cada tag, elemento e propriedade usados neste projeto.

## Índice

1. [Estrutura do HTML](#estrutura-do-html)
2. [Estilos de CSS](#estilos-de-css)
3. [Dependências Externas](#dependências-externas)
4. [Estrutura do Projeto](#estrutura-do-projeto)

## Estrutura do HTML

- **`<!DOCTYPE html>`**: Define o tipo de documento, garantindo que o navegador renderize a página em modo padrão.
- **`<html lang="pt-br">`**: Define o idioma como português do Brasil.
- **`<head>`**: Contém metadados da página.
  - **`<link rel="preconnect">`**: Pré-conecta com fontes externas para melhorar a performance de carregamento.
  - **`<meta charset="UTF-8">`**: Define a codificação de caracteres como UTF-8.
  - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ajusta o layout para dispositivos móveis.
  - **`<link rel="stylesheet" href="style.css">`**: Conecta o arquivo CSS externo com o HTML.
  - **`<title>`**: Define o título da página como "Bolo de Cenoura com Cobertura de Chocolate".

- **`<body>`**: Corpo da página onde o conteúdo principal está localizado.
  - **`<div class="page">`**: Container principal para organizar o conteúdo.
    - **`<img>`**: Exibe a imagem do bolo com atributo `alt` para acessibilidade.
    - **`<main>`**: Elemento principal para o conteúdo da página.
      - **`<section class="About">`**: Seção sobre o bolo, com título `<h1>` e descrição `<p>`.
      - **`<section class="Ingredientes">`**: Lista de ingredientes usando `<ul>` e `<li>`.
      - **`<section class="ModeDePreparo">`**: Seção do modo de preparo.
    - **`<footer>`**: Rodapé com créditos.

## Estilos de CSS

### Seletores Globais
- **`*`**: Remove margens e preenchimentos padrão.
- **`:root`**: Define as variáveis globais para fonte, cor de texto e espaçamento de linha.

### Corpo da Página
- **`body`**: Define uma imagem de fundo e uma cor para quando a imagem não for carregada.

### Classes e Elementos Específicos
- **`.page`**: Estiliza o container principal, incluindo cor de fundo, largura, margem e padding.
- **`.page img`**: Ajusta o tamanho e bordas da imagem para preenchimento total e bordas arredondadas.
- **`h1, h2, p`**: Define tamanhos de fonte, cores e margens específicas para títulos e parágrafos.
- **`ul, li`**: Lista com espaçamento, preenchimento e estilo de marcador.
- **`footer`**: Centraliza o texto do rodapé e ajusta sua cor.

### Propriedades CSS Úteis
- **`background-image` e `background-color`**: Usadas para definir a imagem de fundo e a cor da página.
- **`padding` e `margin`**: Para controlar espaçamento interno e externo.
- **`border-radius`**: Arredonda as bordas de elementos.
- **`font-family`, `color`, `font-size`, `line-height`**: Definem estilo, cor, tamanho e espaçamento entre linhas dos textos.

## Dependências Externas
- **Fonte Google**: O projeto utiliza a fonte "Alice" do Google Fonts.

## Estrutura do Projeto

```
|-- index.html         # Arquivo HTML principal
|-- style.css          # Arquivo CSS com os estilos
|-- assets/            # Pasta de recursos, como imagens
    |-- bolo.jpg       # Imagem do bolo
    |-- bg-bolo.png    # Imagem de fundo da página
    |-- heart.svg      # Ícone de coração para o rodapé
```

## Pré-requisitos

Para visualizar a página corretamente, é necessário ter conexão com a internet para carregar a fonte do Google.

## Licença

Este projeto é apenas para fins de aprendizado e uso pessoal.

---
