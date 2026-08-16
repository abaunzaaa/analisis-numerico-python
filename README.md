# Análisis numérico con Python

Colección de implementaciones y aplicaciones de diferentes **métodos numéricos utilizando Python**, desarrolladas en Jupyter Notebook.

El objetivo de este repositorio es documentar de forma clara el funcionamiento de distintos algoritmos de análisis numérico, combinando su fundamento matemático con implementaciones prácticas, ejercicios aplicados, visualizaciones y análisis de resultados.

Los notebooks han sido organizados y documentados individualmente para facilitar su lectura, ejecución y comprensión.

---

## Contenido

Actualmente el repositorio incluye métodos y aplicaciones relacionados con:

- Búsqueda de raíces de ecuaciones no lineales.
- Solución directa e iterativa de sistemas de ecuaciones lineales.
- Interpolación de datos.
- Ajuste de datos mediante mínimos cuadrados.
- Modelos no lineales y transformación de variables.
- Series de Taylor.
- Método de Newton-Raphson.
- Ecuaciones diferenciales ordinarias.
- Método de Euler.
- Sistemas dinámicos.
- Aplicaciones integradoras de diferentes métodos numéricos.

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
| 09 | [Modelos no lineales](notebooks/09-modelos-no-lineales.ipynb) | Análisis de relaciones no lineales mediante transformaciones de variables, ajuste lineal y comparación utilizando el coeficiente de determinación \(R^2\). |
| 10 | [Series de Taylor](notebooks/10-series-taylor.ipynb) | Construcción de polinomios de Taylor, análisis del error de aproximación y aplicaciones para aproximar funciones, derivadas e integrales. |
| 11 | [Método de Euler para EDO](notebooks/11-metodo-euler-edo.ipynb) | Solución numérica de ecuaciones diferenciales ordinarias y sistemas dinámicos mediante Euler, incluyendo modelos de propagación y presa-depredador. |
| 12 | [Aplicaciones de Análisis Numérico](notebooks/13-aplicaciones-analisis-numerico.ipynb) | Colección de talleres y problemas aplicados que integran diferentes métodos numéricos en contextos matemáticos, físicos y de modelación. |

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
│   ├── 08-minimos-cuadrados.ipynb
│   ├── 09-modelos-no-lineales.ipynb
│   ├── 10-series-taylor.ipynb
│   ├── 11-metodo-euler-edo.ipynb
│   └── 12-aplicaciones-analisis-numerico.ipynb
│
├── .gitignore
└── README.md
```

---

## Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![SymPy](https://img.shields.io/badge/SymPy-3B5526?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

Las principales herramientas utilizadas son:

- **Python** para la implementación de los métodos.
- **NumPy** para operaciones numéricas, vectores y matrices.
- **Matplotlib** para la representación gráfica de resultados.
- **SymPy** para derivación, integración y manipulación simbólica.
- **Pandas** para organizar y visualizar resultados numéricos en algunos ejercicios.
- **Jupyter Notebook** para integrar teoría, código, resultados, gráficas e interpretación.

---

## Enfoque de los notebooks

Cada notebook mantiene, cuando el tema lo permite, una estructura similar:

1. Fundamento matemático del método.
2. Formulación y ecuaciones principales.
3. Implementación en Python.
4. Aplicación a uno o varios problemas.
5. Visualización de resultados.
6. Análisis e interpretación.
7. Conclusiones.

El propósito no es utilizar únicamente funciones predefinidas de bibliotecas, sino **comprender, implementar y analizar los algoritmos numéricos**, observando su comportamiento y sus posibles aplicaciones.

---

## Ejecución

Para ejecutar los notebooks localmente es necesario tener instalado **Python** y **Jupyter Notebook**.

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
pip install numpy matplotlib sympy pandas jupyter
```

Finalmente, iniciar Jupyter Notebook:

```bash
jupyter notebook
```

Desde allí puedes abrir cualquiera de los archivos disponibles en la carpeta `notebooks`.

---

## Autora

**Angie Díaz**

Estudiante de Ingeniería de Sistemas  
Universidad de Medellín
