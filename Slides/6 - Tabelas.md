--- 
marp: true
theme: default
paginate: true
header: '**HTML & CSS para Web**'
footer: 'Prof. Bruno Torres Marques'
---

<center>

# Tabelas no HTML 

<br>

**Prof. Bruno Torres Marques**

---

## 🎯 Objetivos da Aula

- Compreender a estrutura das tabelas em HTML  
- Aprender a utilizar as principais tags: `<table>`, `<tr>`, `<td>`, `<th>`, `<thead>`, `<tbody>`, `<tfoot>`  
- Praticar a criação de tabelas organizadas e semânticas

---

## 📝 O que são tabelas?

- Tabelas organizam dados em linhas e colunas  
- Muito usadas para exibir informações estruturadas  
- Facilitam a leitura e comparação de dados

---

## 🏷️ Tag `<table>`

- Define o início e o fim da tabela  
- Todos os elementos da tabela ficam dentro dela  
- Exemplo:
  ```html
  <table>
    <!-- conteúdo da tabela -->
  </table>
  ```

---

## 🏷️ Tag `<tr>` (table row)

- Cria uma linha na tabela  
- Deve estar dentro da `<table>`  
- Exemplo:
  ```html
  <tr>
    <!-- células da linha -->
  </tr>
  ```

---

## 🏷️ Tag `<td>` (table data)

- Cria uma célula de dados na linha  
- Deve estar dentro de `<tr>`  
- Exemplo:
  ```html
  <td>Conteúdo</td>
  ```

---

## 🏷️ Tag `<th>` (table header)

- Cria uma célula de cabeçalho  
- Geralmente aparece em negrito e centralizada  
- Exemplo:
  ```html
  <th>Nome</th>
  ```

---

## 🧩 Exemplo simples de tabela

```html
<table>
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Bruno</td>
    <td>30</td>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>
```

---

## 🏷️ Tag `<thead>`

- Agrupa o cabeçalho da tabela  
- Facilita a organização e estilização  
- Exemplo:
  ```html
  <table>
    <thead>
      <tr>
        <th>Produto</th>
        <th>Preço</th>
      </tr>
    </thead>
    <!-- corpo da tabela -->
  </table>
  ```

---

## 🏷️ Tag `<tbody>`

- Agrupa o corpo principal da tabela  
- Usada para separar dados do cabeçalho e rodapé  
- Exemplo:
  ```html
  <tbody>
    <tr>
      <td>Notebook</td>
      <td>R$ 3000</td>
    </tr>
  </tbody>
  ```

---

## 🏷️ Tag `<tfoot>`

- Agrupa o rodapé da tabela  
- Usada para totais ou informações finais  
- Exemplo:
  ```html
  <tfoot>
    <tr>
      <td>Total</td>
      <td>R$ 3000</td>
    </tr>
  </tfoot>
  ```

---

## 📚 Estrutura completa de uma tabela

```html
<table>
  <thead>
    <tr>
      <th>Produto</th>
      <th>Preço</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Notebook</td>
      <td>R$ 3000</td>
    </tr>
    <tr>
      <td>Mouse</td>
      <td>R$ 50</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>R$ 3050</td>
    </tr>
  </tfoot>
</table>
```

---

## 🖼️ Visualização da estrutura

- `<thead>`: cabeçalho (títulos das colunas)
- `<tbody>`: corpo (dados principais)
- `<tfoot>`: rodapé (totais ou observações)

---

## 🏷️ Mesclando células: `colspan` e `rowspan`

- `colspan`: mescla células na horizontal  
- `rowspan`: mescla células na vertical  
- Exemplo:
  ```html
  <td colspan="2">Célula mesclada</td>
  <td rowspan="2">Célula vertical</td>
  ```

---

## 🧩 Exemplo com `colspan` e `rowspan`

```html
<table>
  <tr>
    <th>Nome</th>
    <th colspan="2">Contato</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>Email</td>
    <td>Telefone</td>
  </tr>
  <tr>
    <td>Bruno</td>
    <td colspan="2">bruno@email.com</td>
  </tr>
</table>
```

---

## 🎨 Estilizando tabelas com CSS

- Adicione bordas, cores e espaçamento para melhorar a visualização  
- Exemplo:
  ```html
  <style>
    table { border-collapse: collapse; width: 100%; }
    th, td { border: 1px solid #ccc; padding: 8px; }
    th { background: #eee; }
  </style>
  ```

---

## 🛡️ Acessibilidade em tabelas

- Use `<caption>` para descrever a tabela  
- Exemplo:
  ```html
  <table>
    <caption>Lista de produtos e preços</caption>
    <!-- resto da tabela -->
  </table>
  ```
- Utilize `<th scope="col">` e `<th scope="row">` para indicar escopo

---

## 🏷️ Tag `<caption>`

- Descreve o propósito da tabela  
- Fica acima da tabela  
- Exemplo:
  ```html
  <table>
    <caption>Notas dos alunos</caption>
    <!-- conteúdo -->
  </table>
  ```

---

## 📝 Exercício prático

- Crie um arquivo `tabela.html`  
- Monte uma tabela com cabeçalho, corpo e rodapé  
- Utilize `<thead>`, `<tbody>`, `<tfoot>`, `<th>`, `<td>`, `<caption>`, `colspan`, `rowspan`
- Estilize a tabela com CSS

---

## ⚠️ Erros comuns

- Esquecer de fechar tags  
- Usar `<td>` no lugar de `<th>` no cabeçalho  
- Não separar as partes da tabela  
- Não usar `<caption>` para acessibilidade

---

## 💡 Dica

- Use o VS Code para visualizar a tabela  
- Experimente adicionar bordas e estilos com CSS  
- Teste diferentes estruturas e mesclagens de células

---

## 🏁 Resumo da Aula

- Tags de tabela: `<table>`, `<tr>`, `<td>`, `<th>`, `<thead>`, `<tbody>`, `<tfoot>`, `<caption>`, `colspan`, `rowspan`  
- Estrutura e exemplos práticos  
- Boas práticas para tabelas em HTML

---

## 📚 Referências

- [MDN Web Docs - HTML Table](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/table)
- [W3Schools - HTML Tables](https://www.w3schools.com/html/html_tables.asp)

