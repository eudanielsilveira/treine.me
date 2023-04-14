![Wallpaper do projeto Treine.me](https://i.imgur.com/ErK2PJ0.jpg)
# Projeto 02: [Treine.me](https://danielsilveira-dev.github.io/treine.me/)

## Links
[A11y](https://www.a11yproject.com/) | [w3c](https://www.w3c.br/)
## Tecnologias Estudadas
### HTML
Neste projeto, utilizamos tags semânticas!  
Por exemplo:
#### HEADER
Usamos a tag `<header></header>`, para delimitar a área do cabeçalho da nossa página.
```html
    <header>
      <img src="images/logo.svg" alt="Treine.me">
      <nav>
        <ul>
          <li>Home</li>
          <li>Sobre</li>
          <li>Treinar</li>
        </ul>
      </nav>
    </header>
```
### CSS

```css
body {
  margin: 0;
}
.page {
  width: 1000px;
  border: 1px solid red;

  margin: 65px auto 0;
}
```
No `body`, demos um reset na propriedade `margin` dos navegadores definindo o valor inicial como `0`.
Na `class="page"` definimos a largura da página como `width: 1000px;` colocamos uma borda usando a propriedade `border: 1px solid red;` que irá definir a `largura|traçado|cor` da borda.  

## Conceito de FlexBox
Com Flexbox, podemos alinhar nosso conteúdo de forma rápida e fácil.
Conforme abaixo, usamos uma `<div>` como exemplo e definimos dois atributos na nossa tag de bloco.
```css
div {
  display: flex;
  justfify-content: center;
}
```
Com `display: flex;` definimos um contexto dentro do elemento de bloco, e nos permite usar mais atributos para alinhamento, como `justify-content` que usamos no exemplo em cima onde alinhamos os elementos filhos ao centro com o valor de atributo `center`.