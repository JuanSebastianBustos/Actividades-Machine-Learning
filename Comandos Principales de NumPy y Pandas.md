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

**np.array(lista)**<br>
Convierte una lista de Python en un arreglo de NumPy.
![alt text](imagenes\arreglo.png)

**Arreglo bidimensional**<br>
Se pasa una lista de listas.
![alt text](imagenes\arreglo%20bidimensional.png)

**np.zeros((filas, columnas))**<br>
Crea un arreglo lleno de ceros.
![alt text](imagenes\arreglo%20de%20ceros.png)

**np.ones((filas, columnas))**<br>
Crea un arreglo lleno de unos.
![alt text](imagenes\arreglo%20de%20unos.png)

**np.arange(inicio, fin, paso)**<br>
Crea un rango de números.
![alt text](imagenes\arreglo%20con%20rango.png)

**np.random.rand(filas, columnas)**<br>
Genera números aleatorios entre 0 y 1.
![alt text](imagenes\arreglo%20random.png)


### Cambiar forma de un arreglo (reshape)

**reshape(n, m)**<br>
Cambia la forma del arreglo, pero sin alterar sus valores.
![alt text](imagenes\cambiar%20forma.png)


### Concatenación de arreglos

**np.concatenate((a, b))**<br>
Une dos arreglos.
![alt text](imagenes\concatenar.png)

En 2D se puede elegir el eje (axis):<br>
- axis=0: Une por filas
- axis=1: Une por columnas

![alt text](imagenes\concatenar%202d.png)