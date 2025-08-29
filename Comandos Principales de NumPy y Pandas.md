# Comandos Principales de NumPy y Pandas

CAD612023642C-A

**Estudiantes:**
Daniela Alejandra Alvarez
Cristian Camilo Naranjo
Andres Felipe Venegas
Juan Sebastián Bustos

Universidad de Cundinamarca 
30 de agostos del 2025 
Chía


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





