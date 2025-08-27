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



---

# Pandas - Creacion y manipulacion de DataFrames y Series

## 1. Creacion de un DataFrame
Un DataFrame es una estructura de datos tabular similar a una hoja de calculo con filas y columnas etiquetadas.

import pandas as pd

data = {
    'Nombre': ['Jose', 'Carmen', 'Ben', 'Maria'],
    'Apellido': ['Hernandez', 'Villalobos', 'Tennyson', 'Del Prado'],
    'Año de Nacimiento': [1973, 1979, 2005, 1963],
    'Ciudad': ['Tunja', 'Medellin', 'Bellwood', 'Bogota'],
    'Numero de Documento ': ['58496738', '456273812', '1078598612', '845621735']
}

df = pd.DataFrame(data)
print("DataFrame creado:")
print(df)

**Resultado:**
DataFrame creado:
   Nombre    Apellido  Año de Nacimiento    Ciudad Numero de Documento 
0    Jose   Hernandez               1973     Tunja             58496738
1  Carmen  Villalobos               1979  Medellin            456273812
2     Ben    Tennyson               2005  Bellwood           1078598612
3   Maria   Del Prado               1963    Bogota            845621735

---

## 2. Creacion de una Series
Una Series es una estructura unidimensional, similar a una columna de un DataFrame.

Nacimiento = pd.Series([1973, 1979, 2005, 1963, 2015, 1815, '2025', 2001], name='Año de Nacimiento')
print("Serie creada:")
print(Nacimiento)

**Resultado:**
Serie creada:
0    1973
1    1979
2    2005
3    1963
4    2015
5    1815
6    2025
7    2001
Name: Año de Nacimiento, dtype: object

---

## 3. Carga de datos desde un archivo CSV
Pandas permite cargar datos desde archivos externos como CSV.

**Resultado:**

---

## 4. Uso de `head()` para visualizar datos
Muestra las primeras filas del DataFrame (por defecto, 5).

---

## 5. Uso de `dtypes` para ver los tipos de datos
Muestra el tipo de dato de cada columna.

**Resultado:**

---

## 6. Seleccion de columnas
Se pueden seleccionar una o multiples columnas.

**Resultado:**

---

## 7. Conversion de tipos de datos
Podemos convertir el tipo de datos de una columna.



**Resultado:**

