# Documentación de Ejercicios - David Alonso Romero Medina

## Información General
- **Materia:** Fundamentos de Álgebra
- **Tema:** Documentación de matrices con Git Branches
- **Fecha:** 25/11/25
- **Estudiante:** David Alonso Romero Medina
- **Grupo:** 1C

## Objetivo de la Documentación
Este documento detalla el proceso de creación de 14 hojas de cálculo en Excel para representar imágenes como matrices de 30x30 y la aplicación de operaciones matriciales (traspuesta, escalar, suma, resta y composición) para su manipulación.

---

## Pasos a seguir
### 1. Configuración del Lienzo de Matriz (30x30 Píxeles)

Para crear un "lienzo" visible de 30x30 que simule píxeles, se realizaron los siguientes ajustes en las 14 hojas de cálculo:

1.  **Ajuste del Rango:** Se seleccionó el rango de celdas que corresponde a la matriz (Columnas **A** a **AD** y Filas **1** a **30**).
2.  **Ancho de Columna:** Con el rango seleccionado, se estableció un ancho de columna de **2.0** (o su equivalente métrico) para hacer las celdas cuadradas y pequeñas.
3.  **Alto de Fila:** Se ajustó la altura de las filas (1 a 30) a un valor que igualara el tamaño visual del ancho de columna (aproximadamente **15.0** en unidades estándar de Excel).
4.  **Formato Condicional (Escala de Grises):** Se aplicó un formato condicional para que la matriz refleje la imagen según su valor numérico:
    * **Rango de Aplicación:** $\text{A1}:\text{AD30}$.
    * **Regla:** Escala de Color de dos tonos.
    * **Punto Mínimo (Valor 0):** Color **Blanco** ($R:255, G:255, B:255$).
    * **Punto Máximo (Valor 1):** Color **Negro** ($R:0, G:0, B:0$).

Este formato permite representar cualquier valor entre 0 y 1 como una tonalidad de gris.
