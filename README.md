[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maraya12334/Actividad_2_6_Reglas_Asociacion/blob/main/Actividad_2_6_Reglas_Asociacion.ipynb)



# Actividad 2.6: Implementación de Reglas de Asociación

## Objetivo
Aplicar el algoritmo Apriori para identificar asociaciones entre productos utilizando el conjunto de datos Bread Basket.

## Dataset
- Filas analizadas: 18.887
- Transacciones únicas: 9.465
- Productos diferentes: 94

## Herramientas
- Python
- Google Colab
- Pandas
- Mlxtend

## Metodología
Se prepararon los datos y se construyó una matriz de transacciones para aplicar el algoritmo Apriori. Se evaluaron tres configuraciones con soporte mínimo de 0,010, 0,005 y 0,003, y confianza mínima de 0,30.

## Resultados
- Soporte 0,010: 61 conjuntos frecuentes y 19 reglas.
- Soporte 0,005: 114 conjuntos frecuentes y 35 reglas.
- Soporte 0,003: 177 conjuntos frecuentes y 63 reglas.

Se seleccionaron cinco reglas con lift superior a 1 y se analizó una regla rechazada con lift inferior a 1.

## Decisión comercial
Se propone evaluar promociones que combinen café con tostadas, pastelería y sándwiches. Su efectividad deberá validarse con datos de ventas.

## Archivos de resultados
- `comparacion_configuraciones.csv`
- `cinco_reglas_principales.csv`
- `regla_rechazada.csv`
- Notebook de Google Colab (`.ipynb`)
