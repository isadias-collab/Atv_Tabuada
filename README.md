# 🔢 Painel de Tabuadas Dinâmico

## 📚 Exercício de Lógica de Programação com `for`

## 🎯 Sobre o Projeto

Este projeto consiste no desenvolvimento de uma página web interativa que gera automaticamente as **tabuadas do 1 ao 10** ao clicar em um botão.

A atividade tem como objetivo praticar a **estrutura de repetição (`for`)**, laços aninhados e manipulação do DOM com JavaScript.

---

## 🧠 Situação-Problema

Foi proposta a criação de uma ferramenta educacional capaz de gerar automaticamente as tabuadas de multiplicação, organizando-as de forma clara e visualmente estruturada.

O sistema deveria:

- Gerar as tabuadas do 1 ao 10
- Utilizar laços de repetição aninhados
- Exibir os resultados dinamicamente na tela

---

## 🚀 Funcionalidades

✔️ Botão para gerar as tabuadas  
✔️ Laço `for` externo (controla a tabuada atual)  
✔️ Laço `for` interno (realiza as multiplicações)  
✔️ Cálculo automático de 1x1 até 10x10  
✔️ Inserção dinâmica do conteúdo com `.innerHTML`  
✔️ Organização em formato de **cards** com CSS  

---

## 🛠️ Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript  

---

## 🔎 Estrutura do Funcionamento

### 📌 HTML
- Um botão que executa a função `gerarTabuadas()`
- Uma `<div>` com `id="resultado"` onde os resultados são exibidos

### 📌 JavaScript
O sistema utiliza dois laços `for` aninhados:

- O primeiro laço percorre os números de 1 a 10
- O segundo laço realiza as multiplicações de 1 a 10
- Os resultados são armazenados em uma variável `string`
- Ao final, o conteúdo é inserido no HTML com `.innerHTML`

---

## 🎨 Estilização

Cada tabuada é exibida dentro de um **card**, organizado lado a lado utilizando propriedades como:

- `display: flex`
- `flex-wrap: wrap`
- espaçamento entre os elementos

---

## 📂 Como Executar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` no navegador
3. Clique em **Gerar Tabuada**
4. Visualize as tabuadas organizadas na tela

---

## 📘 Conceitos Trabalhados

- Estrutura de repetição `for`
- Laços aninhados
- Manipulação do DOM
- Concatenação de strings
- Organização visual com CSS
- Lógica de programação

---

## 👩‍💻 Objetivo Educacional

Reforçar o raciocínio lógico e a utilização de estruturas de repetição para a construção de soluções dinâmicas em JavaScript.
