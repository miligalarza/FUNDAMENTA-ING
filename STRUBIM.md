 ## DATOS IMPORTANTES

 - Iniciar sesion y seleccionar el proyecto para vincularlo, de CYPE 3D vienen con todos los esfuerzos cargados directamente.
 - Las partes son los elementos aislados, como una chapa, un bulón, una soldadura.
 - Conjuntos: toma el elemento y las chapas soldadas
 - Para generar una vista debemos ir al simbolo de un cubo con un + y poner crear vista, que puede ser una planta o elevación (alzado)
 - Se asignan capas por colores y por elementos, se lo asigna con la etiqueta. A veces se los puede agrupar por peso. Etiquetas + añadir color

## MATERIALES
 - Los perfiles son F-36 los W y F-26 el resto de perfiles
 - Bulones en el 205 son A325 type 1

## UNIONES 
 - Para perfiles que llegan al ala de otro perfil se le pone una chapa frontal.
 - Hacer agujeros en los perfiles no es lo mejor, se busca agujerear las chapa<s y luego soldarlas.
 - Para ver el tipo de unión debemos ver en CYPE 3D el coeficiente de empotramiento, si es menor a 0.3 será articulada y si es mayor a 0.3 será empotrada.
 - Si la unión es articulada se coloca una chapa lateral con pernos en la viga y si es empotrada chapa frontal con bulones y rigidizadores con chapas arriba y abajo.
 - Las cartelas que se usan para rigidizar tendrán en su mayor dimensión el valor de la altura de la viga y en la menor h/2.

## TORNILLOES
Usar 3/4" o 1" y los agujeros tienen 2 mm mas
 
 ## ESPESORES USADOS PARA RIGIDIZADORES Y PLACAS
 -  6.4 mm 1/4"
 -  4.8 mm 3/8"
 -  9.5 mm 3/8"
 - 12.7mm 1/2"
 - 16mm 5/8"
 - 19mm 3/4"

 ## ESPESORES USADOS EN SOLDADUROS
  - 4 mm
  - 6 mm
  - 8 mm
  - 10 mm
TENER EN CUENTA QUE EL ESPESOR MÁXIMO DE LA SOLDADURA SERÁ EL ESPESOR MAS CHICO DE LAS PLACAS A UNIR

 ## CÁLCULO
  - Poner los estados de carga mas desfavorables asi calcula mas rapido
  - Opciones de cálculo: hacer mas grande el tamaño de los elementos finitos, como mucho 100, para que calcule mas rápido
  - ## EL PERFIL PORTANTE ES LA COLUMNA
  - En generar el modelo BIM poner que los esfuerzos minimos de fuerzas son 40 KN y de momento 40 KNm

 ## RESULTADO 
 Se deben revisar los coeficientes de aprovechamiento, no mas del 60% de cada elemento (color amarillo). También revisamos las tensiones de VON MISES teniendo como minimo 190 Mpa y como máximo 230 MPa, se debe evaluar todos los casos de carga pero los de viento son los mas desfavorables, se deve evitar la concentración de carga.
 También se puede revisar los desplazamientos para ver si el empotramiento es correcto o no.
 A veces saldrá que hay elementos que no verifican y eso es porque las soldaduras tienen un cateto que excede el maximo del reglamento, pero es muy poco el exceso. 

  ## LÁMINAS
  Cuando creamos una lámina vamos arriba a escena 3D y vamos a donde está la varita mágica. Poner el mismo divisor de escala en plantas y placas. Luego para etiquetar hacer las ediciones correspondientes para que aparezcan los nombres de las placs por ejemplo.
