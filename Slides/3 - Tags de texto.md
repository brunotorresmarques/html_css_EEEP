--- 
marp: true
theme: default
paginate: true
header: '**HTML & CSS para Web**'
footer: 'Prof. Bruno Torres Marques'
---

# Tags de Texto no HTML  
**Prof. Bruno Torres Marques**

---

## 🎯 Objetivos da Aula

- Conhecer as principais tags de texto do HTML  
- Entender a função de cada tag  
- Praticar a criação de textos estruturados em páginas web

---

## 📝 O que são tags de texto?

- Tags de texto são usadas para estruturar e formatar conteúdos escritos em HTML  
- Permitem organizar títulos, parágrafos, destaques e citações

---

## 🏷️ Tags de título: `<h1>` a `<h6>`

- Usadas para criar títulos e subtítulos  
- `<h1>` é o título principal, `<h6>` o menos importante  
- Exemplo:

```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Seção</h3>
```

---

## 📊 Hierarquia dos títulos

- Ajuda na organização do conteúdo  
- Importante para SEO e acessibilidade  
- Nunca pule níveis sem necessidade (ex: não usar `<h3>` antes de `<h2>`)

---

## 🏷️ Tag `<p>` (parágrafo)

- Usada para criar parágrafos de texto  
- Exemplo:

```html
<p>Este é um parágrafo de exemplo.</p>
```

---

## 🏷️ Tag `<br>` (quebra de linha)

- Insere uma quebra de linha no texto  
- Não possui tag de fechamento  
- Exemplo:

```html
<p>Primeira linha.<br>Segunda linha.</p>
```

---

## 🏷️ Tag `<strong>` (destaque forte)

- Deixa o texto em **negrito**  
- Indica importância semântica  
- Exemplo:

```html
<p>Este texto é <strong>importante</strong>.</p>
```

---

## 🏷️ Tag `<em>` (ênfase)

- Deixa o texto em *itálico*  
- Indica ênfase ou destaque  
- Exemplo:

```html
<p>Este texto está em <em>itálico</em>.</p>
```

---

## 🏷️ Tag `<blockquote>` (citação)

- Usada para destacar citações longas  
- Geralmente aparece com recuo  
- Exemplo:

```html
<blockquote>
  "A simplicidade é o último grau de sofisticação." - Leonardo da Vinci
</blockquote>
```

---

## 🧩 Exemplo prático com várias tags

```html
<h1>Bem-vindo ao HTML!</h1>
<p>HTML é a linguagem de marcação da web.</p>
<h2>Principais tags de texto</h2>
<p>Você pode <strong>destacar</strong> ou <em>enfatizar</em> partes do texto.</p>
<blockquote>
  "Aprender HTML é o primeiro passo para criar sites."
</blockquote>
```

---

## 🛠️ Boas práticas

- Use títulos para organizar o conteúdo  
- Não exagere nas quebras de linha  
- Prefira `<strong>` e `<em>` para dar significado ao texto  
- Use `<blockquote>` para citações reais

---

## ⚠️ Erros comuns

- Usar `<br>` para separar parágrafos (use `<p>`)  
- Não fechar tags corretamente  
- Misturar níveis de títulos sem lógica

---

## 📝 Exercício prático

- Crie um arquivo `tags.html`  
- Adicione um título principal, um subtítulo, dois parágrafos  
- Destaque uma palavra com `<strong>` e outra com `<em>`  
- Inclua uma citação com `<blockquote>`  
- Use `<br>` para quebrar uma linha em um dos parágrafos

---

## 💡 Dica

- Visualize o resultado no navegador  
- Teste diferentes combinações de tags para entender o efeito

---

## 🏁 Resumo da Aula

- Tags de texto: `<h1>` a `<h6>`, `<p>`, `<br>`, `<strong>`, `<em>`, `<blockquote>`  
- Função e exemplos de cada tag  
- Boas práticas para textos em HTML

---

## 📚 Referências

- [MDN Web Docs - HTML: Elementos de texto](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element)
- [W3Schools - HTML Text Formatting](https://www.w3schools.com/html/html_formatting.asp)