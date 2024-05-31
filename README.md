# <U>**Trabajo Final - Data Science I: Fundamentos para la Ciencia de Datos - Coderhouse**</U>
## Alumna: Ana Paula Alvarez Pringles
### **_Comisión: 60935_**
### **_Porfesor: Jorge Ruiz_**

#**Determinación del precio de diamantes**

##Abstract

La tasación de joyas establece el valor de una pieza. Esta puede verse influenciada no solo por el  material a ser tasado sino también por la complejidad de la pieza, su fabricación, diseño o antiguedad pueden ser factores importantes a tener en cuenta.

Este proyecto se encuentrá orientado a optimizar el proceso de tasación dentro de la industria de los diamantes.

Para este proyecto se utilizó un dataset poveniente de kaggle.com. Cuenta con 54.000 registros de diferentes gemas con sus precios y caracterizadas por sus dimensiones y distintas variables cualitativas indicadoras de calidad.

Podemos decir que existe una relación entre el precio y el peso en quilates, y, que este último tiene relacion a su vez con el resto de las medidas físicas (ancho, alto y profundidad). Pero al contrario de lo esperado, la claridad de la gema si sería una variable involucrada en el precio de los diamantes, así como tambien el color de la gema (tal vez en menor medida), pero no así la calidad del corte. Esto fue llevado a cabo con mejor desempeño mediante una regresión lineal múltiple.

##Objetivo
Estimar el precio de las gemas de acuerdo a las caracteristicas físicas mediante un modelo de regresión.

##Contexto comercial
Este proyecto está orientado a pequeños o medianos locales, que tal vez recién comienzan en el rubro, a facilitar el proceso mencionado ante la falta ya sea de personal con experiencia o instrumentos correspondientes para una adecuada determinación del precio.

Este análisis tiene como objetivo complementar el proceso de tasación de gemas, ayudando a su simplificación, aproximando el precio de las mismas mediante diferentes características.

##Hipótesis:
* El precio se encuentra determinado pricipalmente por el tamaño 'carat' de la gema y menos por la claridad de la misma. es decir por las dimensionas más que por un atributo de calidad.
* De las variables de calidad física, influye más en el precio la calidad del corte que el color de la gema.

* # Descripción del data set

Este data set incluye 10 variables que describen los diamantes, como el precio y otros atributos físicos.

**Atributos físicos:**
* Price: precio en dólares.
* Carat: es una medida que especifica el peso de un diamante.
* Cut: indica la calidad del corte del diamante. Las categorías de peor a mejor son: Fair, Good, Very Good, Premium, Ideal.
* Color: de J (peor) a D (mejor). Los colores van del incoloro al amarillo claro o marrón claro.
* Clarity: Indica cuanlimpio es la gema. Las categorias de peor a mejor son:I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF.

**Dimensiones:**
* x largo en mm.
* y ancho en mm.
* z profundidad en mm.

Depth / Profundidad (%) = z / media(x, y)

Table width / Ancho de la cara plana relativo a la parte mas ancha (%).

Estas dos últimas variables afectan la forma en que refleja la luz en el diamante.

![texto del enlace](https://drive.google.com/uc?id=1irNvAUer3dXiJLBAdTN2JyObTCv8rp1n)
