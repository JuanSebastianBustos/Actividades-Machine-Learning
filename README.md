# Semana-1-Diferencias-entre-Machine-Learning-e-Inteligencia-Artificial
Actividad para comprender por medio de conceptos y fuentes, la diferencia entre ML e IA

## Distribución de Trabajo
1. **Definición de IA y ML:** Andres Felipe Venegas
2. **Diferencias clave IA vs. ML:** Juan Sebastián Bustos
3. **Tipos de ML (supervisado, no supervisado, por refuerzo):** Cristian Camilo Naranjo
4. **Conclusión y síntesis:** Daniela Alejandra Alvarez 


# Semana 2 Comandos principales de Numpy
El objetivo de esta tarea es que los estudiantes desarrollen un datasheet en formato Markdown (.md) que contenga los comandos principales de NumPy y Pandas, organizados de manera clara y con ejemplos ejecutados en Google Colab. Esta actividad permitirá a los estudiantes familiarizarse con estas bibliotecas fundamentales para la ciencia de datos, fortaleciendo sus habilidades en manipulación y análisis de datos.

## Distribución de Trabajo
1. **NumPy – Creación y manipulación de arreglos (arrays, reshape, concatenar, operaciones básicas):** Juan Sebastián Bustos 
2. **NumPy – Operaciones estadísticas y funciones avanzadas (mean, std, sum, arange, linspace, random, álgebra lineal):** Andres Felipe Venegas
3. **Pandas – Creación y manipulación de DataFrames y Series (DataFrame, Series, carga de datos, selección de columnas, tipos de datos):** Cristian Camilo Naranjo
4. **Pandas – Operaciones avanzadas en DataFrames (filtros, groupby, merge/join, manejo de valores nulos, exportación/importación):** Daniela Alejandra Alvarez

   + # Semana 2 Pandas – Operaciones avanzadas en DataFrames
  es una de las librerias mas potentes de python para el analisis y manipulacion de datos. Sus *DataFrames*
  permiten trabajar con datos tabulares(como en excel o SQL), aplicando operaciones avanzadas para limpiar,
  transformar y analizar informacion.
+ # *1. Filtros*
  permiten seleccionar filas/columnas segun condiciones logicas.
  + sintaxis:*df[df["columna"]>valor]*.
  + se pueden combinar condiciones con & (AND) y | (OR).
  + # *codigo*
    ![ejemplo de filtros](https://github.com/user-attachments/assets/9ae40f4c-8eff-495e-a54d-99f534f6595a)
  + # *ejecucion*
    ![ejecucion del filtro](https://github.com/user-attachments/assets/b5d88b28-b0af-4302-98f4-bb1b56980a2f)

+ # *2. Agrupacion (groupby)*
  se usa para agrupar datos y aplicar funciones de agregacion(suma,promedio,conteo,etc).
  + ejemplo:*df.groupby("columna")["otra"].mean()*
  +  + # *codigo*
  + ![ejemplo de groupby](https://github.com/user-attachments/assets/61b6e54e-fdbd-4068-8075-e14311174c62)
  + + # *ejecucion*
  + ![ejecucion del filtro](https://github.com/user-attachments/assets/84af0641-0821-4387-b300-c3c1b5d106e1)
+ # *3. Merge/join*
    permiten unir DataFrames de manera similar a SQL.
   + *merge*:combina segun columnas claves(inner,left,right,outer).
   + *join*:une usando indices.
+ # *4. manejo de valores nulos*
  los valores faltantes (NAN)son comunes en datasets.Pandas ofrece metodos para gestionarlos.
  + df.isnull(), df.dropna(), df.fillna(valor).
+ # *5. exportacion/inportacion*
   se puede trabajar facilmente con diferentes formatos de archivo:
    + *importar:* pd.read_csv("archivo.csv") , pd.read_excel("archivo.xlsx")
    + *exportar:* df.to_csv("archivo.csv",index=False),df.to_excel("archivo.xlsx)"
