Tengo esta paleta de colores:

- primary: #d9f5e8 y se llama Mint
- success: #37cbc2 y se llama Teal
- warning: #fb3 y se llama Gold
- danger: #ff6347 y se llama Tomato

A través de un bucle e iterando sobre una lista, tengo que obtener:

- el nombre del modificador de bloque
- el nombre del color
- el valor en RGB del color
- el valor en HSL del color

Tienes a disposición el siguiendte código HTML del componente ".card":

<div class="card">
  <div class="card__color"></div>
  <dl class="card__details">
    <dt class="card__term">Name:</dt>
    <dd class="card__desc card__desc--name"></dd>
    <dt class="card__term">RGB:</dt>
    <dd class="card__desc card__desc--rgb"></dd>
    <dt class="card__term">HSL:</dt>
    <dd class="card__desc card__desc--hsl"></dd>
  </dl>
</div>