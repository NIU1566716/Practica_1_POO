# Practica_1_POO
1- Diagrama de clases:
He intentado poner el menor número de getters y setters posibles, con el siguiente criterio. 
-getter: si y solo si es necesario obtener el atributo para alguna función.
-setter: fundamentalmente para el inventario, ya que creo que tiene sentido que se pueda modificar y verificación del atributo (p. ej. puertas no puede tener un número desorbitado) 
-Respecto a la clase Linia_inventari, he seguido la lógica del ejercicio de marketplace, entonces en lugar de tener un diccionario complejo, tenemos linias por cada codigo (por ende, por cada pieza, y vamos sumando/restando cantidades).
el /etiqueta_contaminació es para indicar que es un atributo derivado 

2- Caso 1
model -> inventari_peces: He puesto que model agrega un inventari en lugar de peces porque en inventari encontramos el objeto y la cantidad (sin embargo, a niveles prácticos funcionaria distinto que el inventario de fábrica y subministrador, ya que no se podría agregar ni quitar piezas y su existencia estaría asociada a model).
setinventari(inventari): He puesto esta interacción porque creo que tiene sentido que se cree el inventario fuera de fabrica, subministrador y model y que luego se le pase como parametro al instanciar el objeto. Simplemente para hacer emfasis.

3- Caso 2
He puesto que elimina_peces del inventari se hace en el registro para simplificar el hecho de que el diagrama no es un factory design ni parece pretenderlo el ejercicio. Más bien, parece que el vehículo se deba instanciar a parte y luego hacer las modificaciones pertinentes.

4- Caso 3
Creo que mas o menos es todo evidente.
