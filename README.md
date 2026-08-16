# Análisis numérico con Python

Colección de implementaciones y aplicaciones de diferentes **métodos numéricos utilizando Python**, desarrolladas en Jupyter Notebook.

El objetivo de este repositorio es documentar de forma clara el funcionamiento de distintos algoritmos de análisis numérico, combinando su fundamento matemático con implementaciones prácticas, ejercicios aplicados, visualizaciones y análisis de resultados. Los notebooks han sido organizados y documentados individualmente para facilitar su lectura, ejecución y comprensión.

---

## Contenido

Actualmente el repositorio incluye métodos para:

- Búsqueda de raíces de ecuaciones no lineales.
- Solución directa e iterativa de sistemas de ecuaciones lineales.
- Interpolación de datos.
- Ajuste lineal mediante mínimos cuadrados.

---

## Notebooks

| # | Método | Descripción |
|---|---|---|
| 01 | [Método de Bisección](notebooks/01-biseccion.ipynb) | Aproximación de raíces mediante reducción sucesiva de un intervalo con cambio de signo. Incluye diferentes aplicaciones matemáticas y físicas. |
| 02 | [Método de Posición Falsa](notebooks/02-falsa-posicion.ipynb) | Aproximación de raíces utilizando rectas secantes y conservación del intervalo con cambio de signo. Incluye aplicaciones y representación geométrica. |
| 03 | [Método de Jacobi](notebooks/03-metodo-jacobi.ipynb) | Solución iterativa de sistemas de ecuaciones lineales mediante implementaciones por sumatorias y matrices, incluyendo análisis de convergencia. |
| 04 | [Método de Gauss-Seidel](notebooks/04-metodo-gauss-seidel.ipynb) | Solución iterativa de sistemas lineales utilizando inmediatamente los valores calculados en cada iteración. Incluye implementaciones matriciales y mediante sumatorias. |
| 05 | [Eliminación Gaussiana](notebooks/05-eliminacion-gaussiana.ipynb) | Solución directa de sistemas lineales mediante eliminación hacia adelante y sustitución hacia atrás, incluyendo un caso con pivote inicial igual a cero. |
| 06 | [Interpolación de Lagrange](notebooks/06-interpolacion-lagrange.ipynb) | Construcción de polinomios interpolantes mediante la formulación de Lagrange y aplicación sobre conjuntos de datos experimentales. |
| 07 | [Interpolación Polinomial Simple](notebooks/07-interpolacion-polinomial-simple.ipynb) | Construcción de polinomios interpolantes mediante sistemas lineales, con aplicaciones sobre datos experimentales, población y crecimiento biológico. |
| 08 | [Mínimos Cuadrados](notebooks/08-minimos-cuadrados.ipynb) | Ajuste lineal de datos experimentales mediante mínimos cuadrados y análisis gráfico de los modelos obtenidos. |

---

## Organización del repositorio

```text
analisis-numerico-python/
│
├── notebooks/
│   ├── 01-biseccion.ipynb
│   ├── 02-falsa-posicion.ipynb
│   ├── 03-metodo-jacobi.ipynb
│   ├── 04-metodo-gauss-seidel.ipynb
│   ├── 05-eliminacion-gaussiana.ipynb
│   ├── 06-interpolacion-lagrange.ipynb
│   ├── 07-interpolacion-polinomial-simple.ipynb
│   └── 08-minimos-cuadrados.ipynb
│
├── .gitignore
└── README.md
````

---

## Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat\&logo=jupyter\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![SymPy](https://img.shields.io/badge/SymPy-3B5526?style=flat)

Las principales herramientas utilizadas son:

* **Python** para la implementación de los métodos.
* **NumPy** para operaciones numéricas y matriciales.
* **Matplotlib** para la representación gráfica de resultados.
* **SymPy** para cálculos simbólicos en algunos métodos.
* **Jupyter Notebook** para integrar teoría, código, resultados y visualizaciones.

---

## Enfoque de los notebooks

Cada notebook mantiene una estructura similar:

1. Fundamento matemático del método.
2. Implementación en Python.
3. Aplicación a uno o varios problemas.
4. Visualización de resultados cuando corresponde.
5. Interpretación de los resultados.
6. Conclusiones.

El propósito no es utilizar únicamente funciones predefinidas de bibliotecas, sino comprender e implementar los algoritmos numéricos y analizar su comportamiento.

---

## Métodos incluidos

### Búsqueda de raíces

Se implementan métodos numéricos para encontrar aproximaciones de raíces de ecuaciones no lineales.

Actualmente se incluyen:

* Método de Bisección.
* Método de Posición Falsa.

Estos métodos utilizan intervalos donde existe un cambio de signo y permiten analizar diferentes estrategias para aproximar una solución.

---

### Sistemas de ecuaciones lineales

El repositorio incluye métodos directos e iterativos para resolver sistemas lineales.

#### Métodos iterativos

* Método de Jacobi.
* Método de Gauss-Seidel.

En estos notebooks se analiza el proceso iterativo, la convergencia y diferentes formas de implementación.

#### Método directo

* Eliminación Gaussiana.

Se estudia la transformación del sistema a una matriz triangular superior y la posterior sustitución hacia atrás.

---

### Interpolación

La interpolación permite construir funciones que pasan por un conjunto de datos conocidos.

Actualmente se incluyen:

* Interpolación de Lagrange.
* Interpolación Polinomial Simple.

Los ejercicios permiten analizar la construcción de polinomios, el comportamiento entre los puntos conocidos y las diferencias entre interpolación y extrapolación.

---

### Ajuste de datos

Se incluye el método de **mínimos cuadrados** para construir una recta que represente la tendencia general de un conjunto de datos.

A diferencia de la interpolación, el modelo obtenido no necesita pasar exactamente por todos los puntos, sino minimizar globalmente las diferencias entre los valores observados y los valores calculados.

---

## Ejecución

Para ejecutar los notebooks localmente es necesario tener instalado Python y Jupyter Notebook.

Puedes clonar el repositorio con:

```bash
git clone https://github.com/abaunzaaa/analisis-numerico-python.git
```

Luego ingresar al proyecto:

```bash
cd analisis-numerico-python
```

Instalar las principales dependencias:

```bash
pip install numpy matplotlib sympy jupyter
```

Finalmente, iniciar Jupyter Notebook:

```bash
jupyter notebook
```

Desde allí puedes abrir cualquiera de los archivos disponibles en la carpeta `notebooks`.

---

## Autora

**Angie Díaz**

Estudiante de Ingeniería de Sistemas -
Universidad de Medellín
