➢ De caja negra: (o de comportamiento) Sólo se comprueba la funcionalidad, es decir,
si la salida es adecuada en función de los datos de entrada, sin fijarse en el
funcionamiento interno. En las pruebas de caja negra también serán necesarios
múltiples casos de prueba que incluyan todos los grupos de entradas que tienen
comportamientos distintos

➢ De caja blanca: (o estructurales) Se analiza la estructura interna del programa
inspeccionando el código.

```java
(I) public void suma () {
(1) Scanner teclado = new Scanner(System.in);
(2) int a, b, resultado;
(3) System.out.println("Introduce un número positivo");
(4) a = teclado.nextInt();
(5) System.out.println("Introduce otro número positivo");
(6) b = teclado.nextInt();
(7)y(8) if ((a>0) && (b>0)) {
(9) resultado = a + b;
(10) System.out.println("El resultado es: "+resultado);
} else {
(11) System.out.println("No son positivos");
}
(12) teclado.close();
(F) }
```

![image](https://github.com/Juanies/Pruebas-software/assets/80675013/85108540-ce56-441b-ab94-7fd90c48e48d)



![awa](https://github.com/Juanies/Pruebas-software/assets/80675013/ea84104a-98f3-4f6c-88b0-c12df42fb107)
