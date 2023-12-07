## RGB e RGBA em HTML

Em HTML e CSS, as cores podem ser representadas de diversas maneiras, sendo duas delas RGB e RGBA.

### RGB (Red, Green, Blue)

O modelo de cor RGB utiliza a combinação de três componentes: vermelho (Red), verde (Green) e azul (Blue). Cada componente é representado por um valor que varia de 0 a 255. A combinação desses valores define a cor final.

Exemplo em CSS:
```css
div {
  background-color: rgb(255, 0, 0); /* Vermelho puro */
}

### RGBA (Red, Green, Blue, Alpha)

O modelo RGBA é uma extensão do RGB, acrescentando um quarto componente chamado alfa (Alpha). O componente alfa controla a transparência da cor, variando de 0 (totalmente transparente) a 1 (totalmente opaco).


Exemplo em CSS:

div {
  background-color: rgba(255, 0, 0, 0.5); /* Vermelho com 50% de transparência */
}

