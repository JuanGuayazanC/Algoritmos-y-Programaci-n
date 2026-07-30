# Algoritmos y Programación (AYPR)

Repositorio general del curso Algoritmos y Programación (AYPR-6201), que agrupa —mediante submódulos de git— las actividades académicas y los proyectos del curso.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para clonar este repositorio junto con todo su contenido, ver [Cómo clonar](#cómo-clonar).

## Estructura del proyecto

```
Algoritmos-y-Programaci-n/
├── Parciales/         # Submódulo → Parcial
├── Tareas/             # Submódulos → Tarea 1 a Tarea 9
├── Quices/              # Submódulos → Impares, Trenes, Strings, Saber 11
├── Talleres/             # Submódulo → Ordenamientos iterativos
├── Contest/               # Submódulo → Arenas
├── TrabajosEnClase/        # Submódulos → ejercicios y entregables sueltos de clase
└── Proyectos/                # Submódulos → Ahorcadito, Juego de Trenes y Saber 11 2020
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

- El curso avanza en tercios (no reflejados aquí): cada uno introduce estructuras más complejas sobre las del anterior (secuencia → condicionales/subprogramas → recursión → ciclos/arreglos → búsqueda/ordenamiento). El orden real dentro de cada categoría lo indica el número de cada tarea/quiz.
- Cada actividad, ejercicio o entregable vive en su propio repositorio, con sus archivos `.py` ejecutables de forma independiente.
- Cuando un ejercicio tiene una versión posterior que lo corrige o extiende (por ejemplo, una refactorización o una versión más completa), ambas quedan en el mismo repositorio como commits sucesivos, para conservar la trazabilidad de esa evolución.
- `TrabajosEnClase/` agrupa los ejercicios guiados de práctica y los entregables puntuales de cada sesión, distintos de las tareas evaluadas formalmente.
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
