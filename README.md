# Algoritmos y Programación

Repositorio general del curso: consolida los temas y conceptos vistos, y agrupa las actividades académicas y los proyectos como [submódulos de git](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## Estructura del proyecto

```
Algoritmos-y-Programaci-n/
├── Tercio1/    # Submódulos → Parcial, Tareas 1-5 y Trabajos en clase del tercio 1
├── Tercio2/     # Submódulos → Quices, Contest 1, Tareas 6-9 y Trabajos en clase del tercio 2
├── Tercio3/      # Submódulos → Quices, Taller de ordenamientos y Trabajos en clase del tercio 3
└── Proyectos/     # Submódulos → Ahorcadito, Juego de Trenes y Saber 11 2020
```

## Temas del curso

El curso recorre la construcción de algoritmos y programas en Python, de lo más simple a lo más estructurado:

- Algoritmos en seudolenguaje y su traducción a lenguaje de computador.
- Estructuras condicionales y subprogramas (funciones).
- Recursión: caso base y caso recursivo.
- Ciclos, arreglos, matrices y secuencias (incluyendo strings).
- Algoritmos de búsqueda y de ordenamiento, iterativos y recursivos (Merge Sort).
- Aplicación de lo anterior en proyectos completos (juegos y procesamiento de datos).

## Cosas a tener en cuenta

- El curso avanza en tercios: cada uno introduce estructuras más complejas sobre las del anterior (secuencia → condicionales/subprogramas → recursión → ciclos/arreglos → búsqueda/ordenamiento).
- Cada actividad (tarea, taller, quiz, contest) vive en su propio repositorio, con sus archivos `.py` ejecutables de forma independiente.
- Los "Trabajos en clase" son ejercicios guiados de práctica dentro de cada tercio, distintos de las tareas evaluadas formalmente.
- Los proyectos (`Proyectos/`) son entregables más grandes que integran varios conceptos del curso en una aplicación completa, y tienen su propia estructura de README (con estado del proyecto, licencia, etc.), distinta de las actividades académicas sueltas.

## Herramientas

- **Python 3** — lenguaje usado en todo el curso.

## Cómo clonar

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Algoritmos-y-Programaci-n.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```

Para traer las últimas actualizaciones de cada repositorio enlazado:

```bash
git submodule update --remote --merge
```
