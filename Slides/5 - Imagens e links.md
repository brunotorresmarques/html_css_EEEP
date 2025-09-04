--- 
marp: true
theme: default
paginate: true
header: '**HTML & CSS para Web**'
footer: 'Prof. Bruno Torres Marques'
---

<center>

# Imagens e Links no HTML  

<br>

**Prof. Bruno Torres Marques**

---

## 🎯 Objetivos da Aula

- Aprender a inserir imagens em páginas HTML  
- Compreender caminhos relativos e absolutos  
- Utilizar links para navegação e recursos externos  
- Explorar atributos importantes das tags `<img>` e `<a>`

---

## 🖼️ Imagens no HTML: tag `<img>`

- Usada para exibir imagens em páginas web  
- Não possui tag de fechamento  
- Principais atributos: `src`, `alt`, `width`, `height`

---

## 🏷️ Atributo `src`

- Define o caminho da imagem  
- Pode ser relativo ou absoluto  
- Exemplo relativo:  
  ```html
  <img src="imagens/logo.png" alt="Logo">
  ```
- Exemplo absoluto:  
  ```html
  <img src="https://exemplo.com/logo.png" alt="Logo">
  ```

---

## 🏷️ Atributo `alt`

- Texto alternativo exibido se a imagem não carregar  
- Importante para acessibilidade  
- Exemplo:  
  ```html
  <img src="foto.jpg" alt="Foto de perfil">
  ```

---

## 🏷️ Atributos `width` e `height`

- Definem largura e altura da imagem  
- Valores em pixels ou porcentagem  
- Exemplo:  
  ```html
  <img src="foto.jpg" alt="Foto" width="200" height="150">
  ```

---

## 📁 Caminhos relativos

- Referenciam arquivos dentro do próprio projeto  
- Exemplo:  
  ```html
  <img src="imagens/foto.jpg" alt="Foto">
  ```
- Vantagem: funciona em qualquer computador, desde que a estrutura de pastas seja mantida

---

## 🌐 Caminhos absolutos

- Referenciam arquivos pela URL completa  
- Exemplo:  
  ```html
  <img src="https://site.com/imagem.jpg" alt="Imagem">
  ```
- Usado para imagens hospedadas externamente

---

## 🧩 Exemplo prático de imagens

```html
<h2>Imagem local</h2>
<img src="imagens/paisagem.jpg" alt="Paisagem" width="300">

<h2>Imagem externa</h2>
<img src="https://www.exemplo.com/paisagem.jpg" alt="Paisagem Externa" width="300">
```

---

## 🛠️ Boas práticas com imagens

- Sempre use o atributo `alt`  
- Prefira caminhos relativos para imagens do projeto  
- Otimize o tamanho das imagens para web

---

## ⚠️ Erros comuns com imagens

- Caminho errado no atributo `src`  
- Esquecer o atributo `alt`  
- Usar imagens muito grandes sem necessidade

---

## 🔗 Links no HTML: tag `<a>`

- Usada para criar hiperlinks  
- Permite navegar entre páginas ou acessar recursos externos  
- Principais atributos: `href`, `target`, `title`

---

## 🏷️ Atributo `href`

- Define o destino do link  
- Pode ser relativo ou absoluto  
- Exemplo relativo:  
  ```html
  <a href="contato.html">Contato</a>
  ```
- Exemplo absoluto:  
  ```html
  <a href="https://www.google.com">Google</a>
  ```

---

## 🏷️ Atributo `target`

- Define como o link será aberto  
- `_self`: mesma aba (padrão)  
- `_blank`: nova aba  
- Exemplo:  
  ```html
  <a href="https://www.google.com" target="_blank">Abrir Google</a>
  ```

---

## 🏷️ Atributo `title`

- Texto exibido ao passar o mouse sobre o link  
- Ajuda na usabilidade  
- Exemplo:  
  ```html
  <a href="contato.html" title="Fale conosco">Contato</a>
  ```

---

## 🧩 Exemplo prático de links

```html
<h2>Link interno</h2>
<a href="sobre.html">Sobre a empresa</a>

<h2>Link externo</h2>
<a href="https://www.exemplo.com" target="_blank" title="Site Externo">Visite nosso site</a>
```

---

## 🛠️ Boas práticas com links

- Use títulos descritivos  
- Prefira links relativos para navegação interna  
- Use `target="_blank"` para sites externos

---

## ⚠️ Erros comuns com links

- Esquecer o atributo `href`  
- Usar links quebrados ou inexistentes  
- Não informar ao usuário que o link abre em nova aba

---

## 📝 Exercício prático

- Crie um arquivo `imagens-links.html`  
- Insira uma imagem local e uma externa  
- Adicione um link interno e um externo  
- Use os atributos `alt`, `title` e `target` corretamente

---

## 💡 Dica

- Teste os caminhos das imagens e links no navegador  
- Organize suas imagens em uma pasta específica no projeto

---

## 🏁 Resumo da Aula

- Tag `<img>`: inserir imagens, atributos e caminhos  
- Tag `<a>`: criar links, atributos e exemplos  
- Diferença entre caminhos relativos e absolutos

---

## 📚 Referências

- [MDN Web Docs - HTML Imagens](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)
- [MDN Web Docs - HTML Links](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/a)
- [W3Schools - HTML Images](https://www.w3schools.com/html/html_images.asp)
- [W3Schools - HTML Links](https://www.w3schools.com/html/html_links.asp)