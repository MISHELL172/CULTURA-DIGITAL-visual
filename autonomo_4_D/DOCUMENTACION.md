# MISHELL RAMOS 
# 23-11-2025
# Ciencia de datos e IA
# Tercero A 

# INTRODUCION 
En este proyecto se analizo y optimizo el codigo original en donde calculamos los numeros primos dentro de un rango de 1 al 100000. En donde el codigo original es generado con un tiempo de ejecucion elevado. 

# PROBLEMAS
No utiliza tecnicas eficientes 
Imprimir cada numero teniendo sobrecarga 
Dificultad en el analisis 

# OPTIMIZACION 
Se creo un funcion optimizada manteniendo el mismo metodo de verificacion pero reduciendo la sobrecarga. Ademas, se implemento un vectorial usando la libreria import numpy as np, en donde pudimos lograr una mejora de rendimiento debido a que NumPy permite ejecutar operaciones grandes. por ende tenemos algunos beneficios como: Eliminacion del costo al momento de imprimir, Reduccion de tiempo, Uso de vectores eficientes. 

# RESULTADOS
una vez realizado el analisis y ejecucion pudimos ver que los tiempos con time.perf_counter() y el analissi con cProfile se pudo obtener los siguientes resultados:
En el codigo original tenemos el tiempo de ejecucion: 0.72298
En el codigo optimizado el tiempo de ejecucion: 0.2073
En el codigo de Numpy el tiempo de ejecucion: 0.000328

# COMCLUSION
Se pudo verificar que al momento de realizar una optimizacion se mejora la aceleracion y reducion de los tiempos de ejecucion y eliminacion de los calculos que no son necesarios con grandes cantidades, ademas con la implementacion de NumPy se pudo realizar el calculo de numeros primos con mas eficiencia y el analisis con cProfile nos permitio identificar las funciones mas costosas pudiendo obtener un codigo mas limpio, facil para ser analizado. 

