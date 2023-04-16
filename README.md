![Wallpaper do projeto Treine.me](https://i.imgur.com/ErK2PJ0.jpg)
# Projeto 02: [Treine.me](https://danielsilveira-dev.github.io/treine.me/)

## Links
[A11y](https://www.a11yproject.com/) | [w3c](https://www.w3c.br/)  

<a href="#fundoGradiente">Fundo Gradiente</a> | <a href="#conceitoFlexBox">Conceito de Flexbox</a>
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

<h2 id="conceitoFlexBox">Conceito de FlexBox</h2>
Com Flexbox, podemos alinhar nosso conteúdo de forma rápida e fácil.
Conforme abaixo, usamos uma `<div>` como exemplo e definimos dois atributos na nossa tag de bloco.
```css
div {
  display: flex;
  justfify-content: center;
}
```
Com `display: flex;` definimos um contexto dentro do elemento de bloco, e nos permite usar mais atributos para alinhamento, como `justify-content` que usamos no exemplo em cima onde alinhamos os elementos filhos ao centro com o valor de atributo `center`.

<h2 id="fundoGradiente">Fundo Gradiente</h2>

```css
elemento {
  background: linear-gradient(180deg, rgba(227, 255, 248, 0) 82.08%, rgba(227, 255, 248, 0.38) 100%);
}
```
Conforme acima, o valor `linear-gradient(valor1, valor2, valor3)` é uma função que possui três valores.  

`valor1` - é a orientação da posição do gradiente, ou, como será a rotação do background, ex: 0 graus, 90 graus, 180 graus, 270 graus ou 360, qual a **rotação de início** desse gradiente.
O valor foi declarado como `180deg`.
```css
elemento {
  background: linear-gradient(180deg, , );
}
```
`valor2` e `valor3` - São as cores, no caso, usamos o rgba para definir a cor.

No caso,rgba significa `red`, `green`, `blue`, `alpha`.




