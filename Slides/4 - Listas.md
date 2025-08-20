--- 
marp: true
theme: default
paginate: true
header: '**HTML & CSS para Web**'
footer: 'Prof. Bruno Torres Marques'
---

# Listas no HTML  
**Prof. Bruno Torres Marques**

---

## 🎯 Objetivos da Aula

- Conhecer os tipos de listas em HTML  
- Aprender a criar listas ordenadas, não ordenadas e de definição  
- Praticar a estruturação de informações em listas

---

## 📝 O que são listas?

- Listas organizam informações em sequência ou grupos  
- Facilitam a leitura e a estruturação do conteúdo  
- Existem três tipos principais em HTML

---

## 🏷️ Lista ordenada: `<ol>`

- Usada para criar listas numeradas  
- Cada item é representado por `<li>`  
- Exemplo:

```html
<ol>
  <li>Primeiro item</li>
  <li>Segundo item</li>
  <li>Terceiro item</li>
</ol>
```

---

## 📊 Características da lista ordenada

- Os itens são numerados automaticamente  
- Ideal para passos, rankings ou sequências lógicas

---

## 🏷️ Lista não ordenada: `<ul>`

- Usada para criar listas com marcadores  
- Cada item é representado por `<li>`  
- Exemplo:

```html
<ul>
  <li>Maçã</li>
  <li>Banana</li>
  <li>Laranja</li>
</ul>
```

---

## 📋 Características da lista não ordenada

- Os itens aparecem com marcadores (bolinhas, quadrados, etc.)  
- Ideal para listas de opções, ingredientes, tópicos

---

## 🏷️ Lista de definição: `<dl>`

- Usada para apresentar termos e suas definições  
- Utiliza `<dt>` para o termo e `<dd>` para a definição  
- Exemplo:

```html
<dl>
  <dt>HTML</dt>
  <dd>Linguagem de marcação para web.</dd>
  <dt>CSS</dt>
  <dd>Folhas de estilo em cascata.</dd>
</dl>
```

---

## 📚 Estrutura da lista de definição

- `<dl>`: lista de definição  
- `<dt>`: termo  
- `<dd>`: descrição/definição

---

## 🧩 Exemplo prático com todos os tipos

```html
<h2>Lista ordenada</h2>
<ol>
  <li>Instalar VS Code</li>
  <li>Criar pasta do projeto</li>
  <li>Iniciar arquivo HTML</li>
</ol>

<h2>Lista não ordenada</h2>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>

<h2>Lista de definição</h2>
<dl>
  <dt>Front-end</dt>
  <dd>Parte visual do site.</dd>
  <dt>Back-end</dt>
  <dd>Parte lógica e de dados.</dd>
</dl>
```

---

## 🛠️ Boas práticas

- Use listas para organizar informações  
- Prefira listas ordenadas para sequências  
- Use listas não ordenadas para tópicos  
- Utilize listas de definição para glossários ou conceitos

---

## ⚠️ Erros comuns

- Esquecer de fechar as tags `<li>`, `<dt>`, `<dd>`  
- Misturar tipos de listas sem necessidade  
- Usar listas para textos que não precisam de estruturação

---

## 📝 Exercício prático

- Crie um arquivo `listas.html`  
- Adicione uma lista ordenada com três passos  
- Uma lista não ordenada com cinco itens  
- Uma lista de definição com dois termos e suas descrições

---

## 💡 Dica

- Visualize o resultado no navegador  
- Experimente combinar listas dentro de outras listas (listas aninhadas)

---

## 🏁 Resumo da Aula

- Listas ordenadas: `<ol>`  
- Listas não ordenadas: `<ul>`  
- Listas de definição: `<dl>`  
- Função e exemplos de cada tipo

---

## 📚 Referências

- [MDN Web Docs - HTML Listas](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/ul)
- [W3Schools - HTML Lists](https://www.w3schools.com/html/html_lists.asp)