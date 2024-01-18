# Taller12

## Problemáticas

#### Fin respuesta

***

### Problema 01
Dado el siguiente arreglo
```
double[][] datos = {{10, 2}, {1, 5}, {6, 2}, {7, 8}};
```

Use un método recursivo que permita encontrar el factorial de cada posición del arreglo. El resultado de cada posición debe ubicarlo en el siguiente arreglo

```
double[][] resultado = new double[4][2];
```

Usar paquete01 y paquete02
***

### Problema 02
Dado el siguiente arreglo
```
double[][] datos1 = {{10, 2, 3}, {1, 5, 8}, {6, 2, 3}, {7, 8, 1}};
double[][] datos2 = {{10, 2, 3}, {1, 5, 8}, {6, 2, 3}, {7, 8, 1}};
```
A través de un método recursivo encuentre y presente la suma de la posición datos1[n][n] con la posición2[n][n], el resultado ubicarlo en un nuevo arreglo llamado datos3[n][n].


Usar paquete03 y paquete04
***


### Problema 03

Dado los siguientes arreglos
```
double[] bases = {100, 90, 80, 70, 60};
double[] potencias = {2, 3, 2, 2, 1};
```

Encuentre la potencia de las posiciones 0 de datos(base) y datos2(potencia) , use un método recursivo; y el valor de la potencia, asignarle a un arreglo llamado resultado

```
double[] resultado = new int[5];
```

Finalmente, encuentre la suma de los valores del arreglo resultado a través de un método recursivo.

Usar paquete05 y paquete06

### Problema 04 (crear el archivo Problema05.java)

Dado el siguiente arreglo
```
String[] dataInicial = {"100", "90", "1n", "10", "H1", "H2"};
```

Obtener como resultado un arreglo con las siguientes características:

```
int[] dataFinal = {100, 90, 0, 10, 0, 0};
```
Presentar dataFinal

Usar el método toInt de la clase NumberUtils, revisar la información en  https://commons.apache.org/proper/commons-lang/javadocs/api-release/index.html

Usar paquete07 y paquete08
