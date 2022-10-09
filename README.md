# Evidencia07

Las clases describen un carro de compras y una calculadora, dependiendo la primera de las operaciones de la segunda, para que, dentro del contexto que se da, se pueda calcular un total y un subtotal de los productos presentes en el propio carro.

El atributo de la clase CarroCompra es una matriz de int de 2 por 5.
Consta de los métodos privados calcularTotal, y subTotal, este último generando la dependencia con la clase calculadora. Además, esta clase posee un método público, mostrarTotal, donde retorna el int que da la función calcularTotal.

Los atributos de la clase Calculadora son dos int, n1 y n2.
Fuera de los setters para este parámetro, tenemos dos métodos públicos, el primero, sumar, que retorna la suma de n1 y n2, y multiplicar, que retorna el producto de estos dos.
