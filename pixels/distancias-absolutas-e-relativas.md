# Distâncias absolutas <length>

São fixas e não alteram seu valor.

unidade     Nome                  Equivalência
cm          Centímetros           1cm = 96px/2.54
in          Inches (polegadas)    1in = 2.54cm = 96px
px          Pixels                1px = 1/96th of 1in

* o mais comin e mais utilizado é o **px**
* não recomendado usar cm

# Distâncias relativas

São relativas a algum outro valor, pode ser o elemento pai, ou root, ou o tamanho da tela.

* Benefício: Maior adaptação aos diferentes tipos de tela

Unidade       Relativo a
em            Tamanho da font do pai.
rem           Tamanho da font do elemento raiz (root/html)
vw            1% da viewport width.
vh            1% da viewport height.

<div><p>Exemplo</p></div>
html {
  font-size: 14px; // Para alterar o tamanho de fonte padrão do html (root)
}
div {
  font-size: 32px;
}
p {
  font-size: 1em; // referente ao tamanho de fonte do elemento pai div.
  font-size: 1rem; // referente ao elemento raiz do html que por padrão é 16px.
}
