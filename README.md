# Estructuras de Datos Fundamentales en Python

[![Licencia MIT](https://img.shields.io/badge/Licencia-MIT-blue.svg )](LICENSE)

Este repositorio alberga el **Jupyter Notebook** (`EstructuraDeDatos.ipynb`), una guía práctica y concisa diseñada para explorar la implementación y el uso de las estructuras de datos más esenciales en el ecosistema de Python.

El objetivo principal de este proyecto es doble:
1.  **Demostrar** las funcionalidades y el manejo de las estructuras de datos nativas de Python (Conjuntos y Diccionarios).
2.  **Ilustrar** cómo las estructuras nativas pueden ser utilizadas como base para construir estructuras de datos abstractas más complejas, como Pilas y Colas.

## 📚 Contenido Detallado del Notebook

El cuaderno está estructurado en secciones claras, cada una con ejemplos de código ejecutables y comentarios explicativos.

### 1. Conjuntos (`set`)

Sección dedicada a la estructura de datos **Conjunto**, que garantiza la unicidad de los elementos.
*   **Creación:** Inicialización de conjuntos y eliminación automática de duplicados.
*   **Operaciones:** Verificación de pertenencia (`in`).
*   **Utilidad:** Ideal para la eliminación rápida de duplicados y operaciones matemáticas de conjuntos.

### 2. Diccionarios (`dict`)

Exploración de la estructura de datos clave-valor, fundamental para la gestión de datos mapeados.
*   **Modelado de Datos:** Uso de diccionarios para representar registros complejos (e.g., datos de estudiantes).
*   **Manipulación:** Ejemplos de modificación y eliminación de claves/valores.
*   **Acceso a Metadatos:** Obtención de todas las claves (`keys()`) y valores (`values()`).

### 3. Pilas (Stack - LIFO)

Implementación de la estructura de datos **Pila** (Last In, First Out).
*   **Implementación:** Se utiliza una clase `Pila` que encapsula una lista de Python para simular el comportamiento LIFO.
*   **Métodos Clave:**
    *   `apilar()` (Push): Agrega un elemento al tope.
    *   `desapilar()` (Pop): Elimina y retorna el elemento del tope.
    *   `ver_tope()` (Peek): Retorna el elemento del tope sin eliminarlo.
*   **Ejemplo Práctico:** Demostración de cómo la pila puede ser usada para invertir una cadena de texto.

### 4. Colas (Queue - FIFO)

Implementación de la estructura de datos **Cola** (First In, First Out).
*   **Implementación:** Se utiliza una clase `Cola` que encapsula una lista de Python para simular el comportamiento FIFO.
*   **Métodos Clave:**
    *   `encolar()` (Enqueue): Agrega un elemento al final de la cola.
    *   `desencolar()` (Dequeue): Elimina y retorna el elemento del inicio de la cola.
*   **Ejemplo Práctico:** Simulación de un sistema de gestión de pedidos para ilustrar el orden de procesamiento.

## 🌐 Recurso Adicional: Listas por Comprensión Anidadas

Como complemento a este estudio de estructuras de datos, he desarrollado un recurso web dedicado a una técnica avanzada de manipulación de listas en Python:

### [Listas por Comprensión Anidadas en Python](https://listacomprensionanidadas.netlify.app/ )

Este sitio web, **Python Learning Hub**, se centra en una de las herramientas más elegantes y eficientes para la creación de listas complejas: las **Listas por Comprensión Anidadas**.

El recurso aborda en detalle la aplicación de esta técnica, con un enfoque particular en la **transposición de matrices**.

#### 💡 Contenido Destacado del Sitio Web

| Sección | Contenido Clave |
| :--- | :--- |
| **Conceptos** | Visualización interactiva de la **Transposición de Matrices** (e.g., de 3x4 a 4x3), explicando cómo las filas se convierten en columnas y las dimensiones se invierten. |
| **Ejemplos** | Una **Comparación de Métodos** para la transposición de matrices, contrastando: 1) Listas por Comprensión Anidadas, 2) Bucles Tradicionales, y 3) la función `zip()`. Se destaca que `zip()` es la opción más concisa y eficiente para este caso de uso. |
| **Avanzado** | Explicación del **Orden de Evaluación** en las comprensiones anidadas (el bucle más a la izquierda es el externo). Presentación de **Casos de Uso Prácticos** (cuándo usar y cuándo evitar) para garantizar la legibilidad y el rendimiento del código. |

Este recurso es altamente recomendado para profundizar en la manipulación eficiente de estructuras de datos en Python.

## 🚀 Uso y Requisitos

Para explorar y ejecutar el código de este proyecto, necesitarás:

*   **Python 3.x**
*   **Jupyter Notebook** (o JupyterLab)

**Pasos para Iniciar:**

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    cd nombre-del-repositorio
    ```

2.  **Abrir el Notebook:**
    Inicia Jupyter Notebook en tu terminal y abre el archivo `EstructuraDeDatos.ipynb`.
    ```bash
    jupyter notebook
    ```

## 👨‍💻 Autor

Este proyecto y el recurso web complementario fueron creados por:

**Jacobo Morales Londoño**

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**.

La Licencia MIT es una licencia de software libre permisiva, lo que significa que puedes usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender copias del software, siempre que se incluya el aviso de derechos de autor y el aviso de permiso en todas las copias o partes sustanciales del Software.

Consulta el archivo [LICENSE](LICENSE ) (que debes crear en tu repositorio) para el texto completo de la licencia.

---

*Este README fue generado automáticamente y extendido para incluir recursos adicionales.*
