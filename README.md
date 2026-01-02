# Vectores Geométricos
---

## 1. Definición: ¿Qué es un Vector?
[cite_start]En este contexto (físico/geométrico), nuestros objetos primitivos son **flechas**[cite: 17].

* [cite_start]**Naturaleza:** Es una cantidad caracterizada únicamente por **longitud (magnitud)** y **dirección**[cite: 15, 17].
* **Equivalencia:** Dos vectores son iguales ($\mathbf{v} = \mathbf{w}$) si tienen la misma longitud y dirección, sin importar su posición en el espacio. [cite_start]Son "dibujos" que podemos mover[cite: 18, 19, 20].
* [cite_start]**El Vector Cero ($\vec{0}$):** Un vector especial con longitud 0. Su dirección es indefinida (o todas las direcciones a la vez)[cite: 20, 21].

---

## 2. El Álgebra: Reglas de Dibujo
[cite_start]Se llama "Álgebra" porque definimos reglas formales para sumar y multiplicar cosas, tal como se suman caracteres en una cadena o palabras en un buscador[cite: 1, 2, 23]. [cite_start]Aquí, el signo `+` es una **instrucción de construcción**[cite: 4, 5].

### A. Algoritmo de Suma (La Regla del Triángulo)
[cite_start]La suma $\mathbf{v} + \mathbf{w}$ no es numérica, es un método para crear una nueva flecha[cite: 3, 5].

```mermaid
graph TD
    A[Inicio: Sumar v + w] --> B[Dibujar vector v];
    B --> C[Colocar la COLA de w en la PUNTA de v];
    C --> D[Trazar flecha desde el INICIO de v hasta el FINAL de w];
    D --> E[Resultado: Nuevo vector v+w];
    style A fill:#f9f,stroke:#333
    style E fill:#9f9,stroke:#333


