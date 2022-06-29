# Practicas_profesionales_1
Practicas del Git para PP1


-----   TRABAJO PRACTICO DE ANALISIS SOBRE REGRESION LINEAL --------
El siguiente github contiene una prueba sobre matrices de datos controlados pero de registros desbalanceados (10:1) las pruebas se ejecutaron completamente pero el modelo no podemos considerar que sirve ya que generalizo completamente la solucion y el 100% de los negativos los convirtio en falzos positivos 
https://github.com/arielmeragelman/Practicas_profesionales_1/blob/main/GENERAR_MATRICES_TP.ipynb


El siguiente github tiene el mismo trabajo pero partiendo de matrices que estan inicialmente balanceadas con la misma cantidad de registros cada una
https://github.com/arielmeragelman/Practicas_profesionales_1/blob/main/GENERAR_MATRICES_TP_MATRICES_BALANCEADAS.ipynb
En este caso se ve que el modelo funciona a la perfección, lo que daria a pensar que pudo estar sobreajustado.
Para evaluar esa posibilidad generamos un nuevo arreglo de datos controlados y volvemos a ejecutar el predict con esos datos nuevos que nunca fueron usados para el entrenamiento, y vemos que vuelve a dar un 100% de exito, por lo que si bien no es lo recomendado llegar a dicho valor, podemos concluir que balanceando las matrices el modelo funciona a la perfeccion 
