--- 
marp: true
theme: default
paginate: true
header: '**HTML & CSS para Web**'
footer: 'Prof. Bruno Torres Marques'
---

# Estrutura básica de um documento HTML  
**Prof. Bruno Torres Marques**

---

## 🎯 Objetivos da Aula

- Entender a estrutura fundamental de um documento HTML  
- Conhecer as principais tags: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`  
- Aprender a criar páginas web organizadas e funcionais

---

## 📝 O que é HTML?

- HTML significa **HyperText Markup Language**  
- É a linguagem base para criar páginas web  
- Utiliza **tags** para estruturar o conteúdo

---

## 📄 O que é um documento HTML?

- Arquivo de texto com extensão `.html`  
- Interpretado pelos navegadores  
- Define o conteúdo e a estrutura da página

---

## 🧩 Estrutura mínima de um documento HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Título da Página</title>
  </head>
  <body>
    Conteúdo da página
  </body>
</html>
```

---

## 🏷️ Tag `<!DOCTYPE html>`

- Declara o tipo do documento  
- Indica ao navegador que o arquivo segue o padrão HTML5  
- Deve ser a primeira linha do arquivo

---

## 🏷️ Tag `<html>`

- Envolve todo o conteúdo da página  
- Indica o início e o fim do documento HTML  
- Pode receber atributos, como `lang="pt-br"`

---

## 🌐 Exemplo com atributo de idioma

```html
<html lang="pt-br">
  <!-- conteúdo -->
</html>
```

- O atributo `lang` informa o idioma principal da página

---

## 🏷️ Tag `<head>`

- Contém informações sobre a página (metadados)  
- Não aparece visualmente para o usuário  
- Exemplos de conteúdo: `<title>`, `<meta>`, `<link>`, `<style>`

---

## 🏷️ Tag `<title>`

- Define o título da página (aparece na aba do navegador)  
- Deve estar dentro da tag `<head>`

```html
<head>
  <title>Minha Primeira Página</title>
</head>
```

---

## 🏷️ Tag `<meta>`

- Define metadados, como codificação de caracteres e descrição  
- Exemplo de uso:

```html
<meta charset="UTF-8">
<meta name="description" content="Página de exemplo HTML">
```

---

## 🏷️ Tag `<link>`

- Usada para importar arquivos externos, como CSS  
- Exemplo:

```html
<link rel="stylesheet" href="style.css">
```

---

## 🏷️ Tag `<style>`

- Permite adicionar CSS diretamente no documento  
- Exemplo:

```html
<style>
  body { background-color: #f0f0f0; }
</style>
```

---

## 🏷️ Tag `<body>`

- Contém todo o conteúdo visível da página  
- Textos, imagens, links, tabelas, etc.

---

## 📦 Exemplo completo de documento HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <title>Exemplo Completo</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Bem-vindo!</h1>
    <p>Esta é uma página HTML básica.</p>
  </body>
</html>
```

---

## 🖼️ Estrutura visual do documento

- `<head>`: informações para o navegador  
- `<body>`: conteúdo para o usuário

---

## 🛠️ Boas práticas

- Sempre usar `<!DOCTYPE html>`  
- Definir o idioma com `lang`  
- Utilizar `<meta charset="UTF-8">` para evitar problemas com acentuação  
- Organizar o conteúdo dentro do `<body>`

---

## ⚠️ Erros comuns

- Esquecer o `<!DOCTYPE html>`  
- Não fechar tags corretamente  
- Colocar conteúdo visível dentro do `<head>`

---

## 📝 Exercício prático

- Crie um arquivo `index.html`  
- Escreva a estrutura básica  
- Adicione um título, um parágrafo e um link externo

---

## 💡 Dica

- Use o VS Code para criar e editar arquivos HTML  
- Utilize a extensão Live Server para visualizar as alterações em tempo real

---

## 🏁 Resumo da Aula

- Estrutura básica: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`  
- Função de cada tag  
- Exemplo prático e boas práticas

---

## 📚 Referências

- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3Schools - HTML](https://www.w3schools.com/html/)