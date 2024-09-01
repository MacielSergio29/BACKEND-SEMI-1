# BACKEND-SEMI-1
# Algoritmo Ruta

# Algoritmo de Búsqueda de Rutas en Matriz

## Descripción

Este proyecto implementa un algoritmo propio para encontrar la ruta de menor y mayor costo desde un punto de inicio `I` hasta un punto final `F` en una matriz dada. La matriz contiene valores enteros positivos y negativos que representan los costos de moverse a través de cada celda. 

El algoritmo utiliza una búsqueda en profundidad (DFS) para explorar todas las rutas posibles y calcula los costos acumulados para cada ruta. Finalmente, selecciona y muestra la ruta de menor costo y la de mayor costo.

## Matriz de Ejemplo

A continuación se muestra la matriz utilizada en este proyecto:

[
[-3, -3, 2, -3, -3, -2, 1, 2, 0, 2, 0, 0, 1],
[2, 3, ‘I’, -1, -1, 3, 2, 0, -3, -3, 2, 2, 1],
[1, -3, -3, 2, 1, -3, -3, 2, 1, -2, 2, 3, -3],
[0, 0, 3, 0, -3, -3, -3, 0, 2, 2, 1, 1, -3],
[2, -1, -3, 3, 0, 3, 1, -2, 2, 0, 1, -2, 0],
[0, 3, -1, -1, 2, -2, 2, 2, 1, -2, -3, 0, -2],
[0, 3, 2, 0, 1, 1, 2, 3, -1, -3, 0, 0, -2],
[3, -3, -3, -3, -3, -1, -3, 3, 3, 2, -2, -1, -3],
[-2, -2, 1, 0, 0, 3, 0, 2, 2, -2, -3, -1, 1],
[-3, 3, 0, -1, 3, 1, -2, 3, 0, 3, 2, -2, 0],
[-3, -3, 3, 3, -3, 0, -2, -3, 1, 0, -1, 2, 1],
[-1, 0, 1, 2, ‘F’, 0, -3, 3, 3, -2, -1, -3, 2],
[1, -3, 1, 0, 1, 2, 3, 3, 0, 3, 2, 3, 0]
]


## Requisitos

- Python 3.7 o superior

## Instalación

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio

   python -m venv env
source env/bin/activate  # En Windows usa `env\Scripts\activate`

pip install -r requirements.txt


Uso

	1.	Ejecuta el script principal:
 python main.py


 2.	Resultados: El programa imprimirá la ruta de menor costo y la ruta de mayor costo desde el punto I al punto F.

Ejemplo de Salida

Ruta de menor costo: (costo, ruta)
Ruta de mayor costo: (costo, ruta)
