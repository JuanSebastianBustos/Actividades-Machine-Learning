# Comandos Principales de NumPy y Pandas

CAD612023642C-A

**Estudiantes:**<br>
Daniela Alejandra Alvarez<br>
Cristian Camilo Naranjo<br>
Andres Felipe Venegas<br>
Juan Sebastián Bustos<br>

Universidad de Cundinamarca <br>
30 de agostos del 2025 <br>
Chía

## Creación y manipulación de Arreglos

### Creación de Arreglos

#### **np.array(lista)**<br>
Convierte una lista de Python en un arreglo de NumPy.<br>
![alt text](imagenes/arreglo.png)

#### **Arreglo bidimensional**<br>
Se pasa una lista de listas.<br>
![alt text](imagenes/arreglo%20bidimensional.png)

#### **np.zeros((filas, columnas))**<br>
Crea un arreglo lleno de ceros.
![alt text](imagenes/arreglo%20de%20ceros.png)

#### **np.ones((filas, columnas))**<br>
Crea un arreglo lleno de unos.
![alt text](imagenes/arreglo%20de%20unos.png)

#### **np.arange(inicio, fin, paso)**<br>
Crea un rango de números.
![alt text](imagenes/arreglo%20con%20rango.png)

#### **np.random.rand(filas, columnas)**<br>
Genera números aleatorios entre 0 y 1.
![alt text](imagenes/arreglo%20random.png)


### Cambiar forma de un arreglo (reshape)

#### **reshape(n, m)**<br>
Cambia la forma del arreglo, pero sin alterar sus valores.
![alt text](imagenes/cambiar%20forma.png)


### Concatenación de arreglos

#### **np.concatenate((a, b))**<br>
Une dos arreglos.
![alt text](imagenes/concatenar.png)

En 2D se puede elegir el eje (axis):<br>
- axis=0: Une por filas
- axis=1: Une por columnas<br>
![alt text](imagenes/concatenar%202d.png)


### Operaciones Básicas

#### **Suma**<br>
![alt text](imagenes/suma.png)

#### **Resta**<br>
![alt text](imagenes/resta.png)

#### **Multiplicación**<br>
![alt text](imagenes/multiplicacion.png)

#### **División**<br>
![alt text](imagenes/division.png)

#### **Potencia**<br>
![alt text](imagenes/potencia.png)


### Operaciones con funciones NumPy

#### **np.mean(arreglo)**<br>
Calcula la media (promedio).
![alt text](imagenes/media.png)

#### **np.max(arreglo)**
Devuelve el valor máximo.
![alt text](imagenes/maximo.png)

#### **np.min(arreglo)**
Devuelve el valor mínimo.
![alt text](imagenes/minimo.png)



## B) NumPy -- Operaciones Estadísticas y Funciones Avanzadas

**Responsable:** Andres Felipe Venegas Hernandez

Esta sección cubre funciones estadísticas para el análisis de datos,
métodos para crear arreglos especializados y operaciones de álgebra
lineal.

### Funciones Estadísticas

Para estos ejemplos, usaremos el siguiente arreglo base:

CODIGO import numpy as np \# Arreglo para los ejemplos mi_arreglo =
np.array(\[2, 4, 6, 8, 10, 12\]) print(f"Arreglo base: {mi_arreglo}")

RESULTADO Arreglo base: \[ 2 4 6 8 10 12\]

EJERCICIO #1 CODIGO Suma de elementos: Calcula la suma de todos los
elementos en el arreglo. \# Usando np.sum() suma = np.sum(mi_arreglo)
print(f"La suma de los elementos es: {suma}")

RESULTADO La suma de los elementos es: 42

EJERCICIO #2 CODIGO Mean: Calcular la media aritmética de los elementos
del arreglo \# Usando np.mean() promedio = np.mean(mi_arreglo)
print(f"El promedio de los elementos es: {promedio}")

RESULTADO El promedio de los elementos es: 7.0

EJERCICIO #3 CODIGO \# Usando np.std() desviacion = np.std(mi_arreglo)
print(f"La desviación estándar es: {desviacion:.2f}")

RESULTADO La desviacion estandar es: 3.42

EJERCICIO #4 CODIGO \# Creando una secuencia de 0 a 20, de 2 en 2
secuencia_arange = np.arange(0, 21, 2) print(f"Arreglo con arange(0, 21,
2): {secuencia_arange}")

RESULTADO Arreglo con arange(0, 21, 2): \[ 0 2 4 6 8 10 12 14 16 18 20\]

EJERCICIO #5 CODIGO \# Creando una matriz de 2x4 con números aleatorios
matriz_aleatoria_decimal = np.random.rand(2, 4)
print("Matriz aleatoria de 2x4:")
print(matriz_aleatoria_decimal)

RESULTADO 
Matriz aleatoria de 2x4:
[[0.64860197 0.09059237 0.09140946 0.04148627]
 [0.19075457 0.35098679 0.98677383 0.55237791]]

EJERCIO #6  CODIGO \# Multiplicando arrays
matriz_A = np.array([[1, 2], [3, 4]])
matriz_B = np.array([[5, 0], [0, 5]])

producto = matriz_A @ matriz_B
print("Matriz A:\n", matriz_A)
print("\nMatriz B:\n", matriz_B)
print("\nProducto de A @ B:\n", producto)

RESULTADO

Matriz A:
 [[1 2]
 [3 4]]

Matriz B:
 [[5 0]
 [0 5]]

Producto de A @ B:
 [[ 5 10]
 [15 20]]

