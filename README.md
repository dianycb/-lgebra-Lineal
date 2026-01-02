# Álgebra-Lineal
Apuntes
# Apunte de Clase: Vectores Geométricos

Este apunte sintetiza los conceptos fundamentales sobre vectores geométricos, basado en la transcripción de las clases de Álgebra Lineal.

---

## 1. Definición y Naturaleza

Se distingue entre dos tipos de cantidades físicas utilizadas en ingeniería y física [1]:

*   **Escalares:** Cantidades descritas solo por un número (responden a "¿qué tanto es?") [1, 2].
*   **Vectores:** Cantidades que requieren un **número (magnitud)** y una **dirección** (responden a "¿qué tanto es y hacia dónde?") [2].

En este curso, tomamos estas nociones para construir **estructuras matemáticas abstractas** [3]. Trabajamos con **vectores geométricos**, representados como flechas en el 2-espacio o 3-espacio [3].

### Representación Geométrica
*   La **dirección** de la flecha especifica la dirección del vector [4].
*   La **longitud** de la flecha especifica su magnitud [4].

> **Nota:** En esta etapa, los vectores son puramente **dibujos (flechas)**, no coordenadas numéricas [5].

### Propiedades Fundamentales
1.  **Equivalencia:** Dos vectores son equivalentes (o iguales) si tienen la **misma dirección y longitud**, sin importar su posición en el espacio [5, 6]. $\vec{v} = \vec{w}$.
2.  **El Vector Cero ($\vec{0}$):** Es un vector con **longitud cero**. Su dirección es indefinida (o todas las direcciones); por convención, se le puede asignar cualquier dirección [7, 8].

---

## 2. El Concepto de Álgebra

Aquí, "álgebra" no es el manejo de ecuaciones numéricas, sino el acto de **dar reglas para sumar y multiplicar cosas** [9].

*   El signo "$+$" no es una suma aritmética, es una **instrucción de dibujo** [10].
*   Nos dice *cómo conectar* las piezas (flechas) [11].

---

## 3. Operaciones con Vectores

### A. Suma de Vectores (Regla del Triángulo)
La regla geométrica para $\vec{v} + \vec{w}$ es [12]:
1.  Tomar el vector $\vec{v}$.
2.  Colocar el punto inicial de $\vec{w}$ en el punto final de $\vec{v}$.
3.  El vector resultante va del **inicio de $\vec{v}$ al final de $\vec{w}$**.

#### Propiedades
*   **Conmutatividad:** $\vec{v} + \vec{w} = \vec{w} + \vec{v}$.
    *   *Demostración:* Se prueba con el método del paralelogramo. El orden de dibujo no altera la flecha resultante (diagonal) [13, 14].
*   **Asociatividad:** $(\vec{u} + \vec{v}) + \vec{w} = \vec{u} + (\vec{v} + \vec{w})$.
    *   *Demostración:* Al sumar tres vectores, no importa cuáles se agrupen primero; el dibujo final conecta el inicio del primero con el final del último [15, 16].

### B. Multiplicación por un Escalar
Si $\vec{v}$ es un vector y $\alpha$ es un escalar, el producto $\alpha\vec{v}$ se define así [17]:

| Propiedad | Definición |
| :--- | :--- |
| **Longitud** | $|\alpha|$ veces la longitud de $\vec{v}$. |
| **Dirección** | • Misma que $\vec{v}$ si $\alpha > 0$.<br>• Opuesta a $\vec{v}$ si $\alpha < 0$.<br>• Vector $\vec{0}$ si $\alpha = 0$. |

---

## 4. Independencia de Coordenadas

Un concepto crucial es que **no existen las coordenadas** en este sistema inicial [18].
*   El universo matemático consta solo de flechas y reglas de dibujo.
*   Las demostraciones se realizan manipulando los dibujos, no asignando valores $(x, y)$ [13, 18].

> **Analogía:** El Álgebra Lineal es como aprender la gramática de un idioma nuevo. El signo "$+$" es un manual de instrucciones que nos dice qué pieza conectar y dónde para construir el objeto final [19].

--------------------------------------------------------------------------------
Opción B: Si prefieres mantener el archivo .tex
Si tu intención es guardar el archivo fuente LaTeX en GitHub para que otros lo descarguen y compilen, te recomiendo añadir un archivo .gitignore para no subir los archivos basura que genera LaTeX (.aux, .log, etc.).
Estructura ideal para el repositorio:
1. main.tex (El código que te di en la respuesta anterior).
2. .gitignore (Crea este archivo y pega el siguiente contenido):
# Archivos de compilación LaTeX a ignorar en GitHub
*.aux
*.log
*.out
*.synctex.gz
*.toc
*.fls
*.fdb_latexmk
*.pdf
