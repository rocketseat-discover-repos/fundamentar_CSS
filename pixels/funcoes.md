# Funções

Em programação, funções são reconhecidas por causar um reaproveitamento de código.

* rgb()
* hsl()
* url()
* calc()

<div class='box'></div>

body { // O elemento body por padrão não possui height
  height: 100vh; // Devido a isso o mesmo deve ser definido
  margin: 0;
}

.box {
  height: calc(100% - 40px); // aplica a % em cima do elemento pai body
  width: 400px;
  background-image: url(http://source.unsplash.com/random);
  background-repeat: no-repeat;
}