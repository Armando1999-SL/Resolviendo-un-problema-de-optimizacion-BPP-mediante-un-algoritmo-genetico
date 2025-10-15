# Solución al Problema de Empaquetamiento de Contenedores (Bin Packing Problem) utilizando Algoritmos Genéticos

Este proyecto aborda la solución de un problema clásico de optimización conocido como el Problema de Empaquetamiento de Contenedores o Bin Packing Problem (BPP).

## Descripción del problema

Dado un conjunto de n objetos con pesos w1, w2, ..., wn y una cantidad ilimitada de contenedores con capacidad fija C, el objetivo es colocar todos los objetos en el menor número posible de contenedores, sin que la suma de los pesos en ningún contenedor supere su capacidad máxima.

Aunque es fácil de entender, el BPP es un problema NP-duro, lo que significa que es computacionalmente complejo y no existe un algoritmo exacto eficiente que garantice encontrar siempre la solución óptima en un tiempo razonable.

## Enfoque de solución

Dado que los métodos exactos no son viables para instancias grandes, en este proyecto utilizamos una metaheurística: el Algoritmo Genético (AG).

El AG es una técnica inspirada en los principios de la evolución natural, como:
- Selección natural
- Reproducción
- Mutación

Esta metaheurística permite encontrar soluciones aproximadas de alta calidad a problemas complejos como el BPP. Aunque no garantiza el óptimo global, ofrece resultados muy cercanos con un tiempo de ejecución razonable.

## Resultados

Nuestra implementación ha mostrado soluciones muy cercanas al óptimo en diversas instancias del problema, lo cual evidencia la eficacia del algoritmo genético y la solidez de nuestra implementación.

## Archivos del repositorio

- **codigo.ipynb**:  
  Contiene la implementación completa del algoritmo genético, desarrollada por mí y un compañero de maestría.

- **instancia#.txt**:  
  Archivos de prueba, cada uno representando un conjunto distinto de objetos con diferentes pesos. Estas instancias se usan para poner a prueba el algoritmo.

- **reporte.pdf**:  
  Documento que describe en detalle:
  - El problema del Bin Packing y su modelado matemático
  - El funcionamiento del algoritmo genético
  - Los resultados obtenidos con distintas instancias

---

Este proyecto es una muestra del uso efectivo de técnicas de inteligencia artificial inspiradas en la naturaleza para resolver problemas computacionales complejos.
