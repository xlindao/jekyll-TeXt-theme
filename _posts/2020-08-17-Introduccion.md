---
title: Introducción a la Ingeniería de Software

---
##   ¿Que es Software? 
![imagen ](https://concepto.de/wp-content/uploads/2015/03/software-1-e1550080097569.jpg)
---


Programas de computo y su documentación asociada: requerimientos,
modelos de diseño y manuales de usuario.
El software puede ser genérico o ad hoc.
  Genérico: desarrollado para venderse a múltiples clientes (Excel, Word,
etc.)
  Ad hoc: desarrollado bajo demanda del cliente a un desarrollador
específico.



## La Ingeniería de Software
Una disciplina de la Ingeniería que concierne a todos los aspectos de
la producción de software
Los Ingenieros de Software deben:
 Adoptar un enfoque sistemático para llevar a cabo su trabajo
 Utilizar las herramientas y técnicas más apropiadas dependiendo:
- del problema a resolver,
- las restricciones del desarrollo y
- los recursos disponibles.
---
## ¿Qué es un proceso de software?
Un conjunto estructurado de actividades, cuya meta es el
desarrollo o evolución de un software.
Algunas actividades genéricas en todos los procesos de software son:
- Especificación, que debe hacer el software y cu´ales son sus
especificaciones de desarrollo.
- Desarrollo, producción del sistema de software
- Validación, verificar que el software cumple con lo solicitado por el
cliente.
- Evolución, cambiar/adaptar el software a las nuevas demandas
 ---
## ¿Cuáles son los atributos de calidad de software? 
El software debe proveer la funcionalidad y desempeño requeridos por el usuario y debe ser
mantenible, confiable y aceptable.
- Mantenible, el software debe poder evolucionar para continuar
  cumpliendo con las especificaciones.
- Confiable, el software no debe causar daños físicos o económicos en
  el caso de que falle
- Eficiente, el software no debe desperdiciar los recursos del sistema
- Aceptable, el software debe ser aceptado por los usuarios para los
que fue diseñado. Debe ser ***entendible, utilizable y compatible*** con
otros sistemas

---
##  ¿Cómo se hace un software?
***Conceptos importantes***
- Personas los que trabajan
- Producto lo que se obtiene
- Proyecto la pauta a seguir para desarrollar un producto
- Proceso la pauta a seguir para desarrollar un proyecto
![como, se hace](https://github.com/xlindao/xlindao.github.io2/blob/master/fff.png?raw=true)
---
## Modelo de proceso de software

### Modelo en Cascada
![Modelo en Cascada](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQd8sM9jnLt9InduYkwc4Za_pACZWD9ye24ew&usqp=CAU)


***Figura 1:Modelo en Cascada***


En la figura anterior se muestra el modelo en cascada que es un método 
que ordena las etapas del ciclo de vida de software, porque para poder 
continuar debe cada etapa debe esperar que la anterior haya concluido,
lo malo es que al presentar un error, no puedes regresar a correjirlo, 
ya que este es muy estricto y no puedes saltar pasos.
### Modelo Iterativo
![Modelo Iterativo](https://aurumsol.com/espanol/articulos/art1/images/iterativo.jpg)

***Figura 2:Modelo en Iterativo***

El modelo iterativo es un modelo incremental, en este el cliente no sabe lo que requiere y presentas el
producto como se ve en la imagen , si el cliente no esta satisfecho, se le va añadiendo nuevas funciones.


***Ventajas***
- El cliente verifica los avances y los beneficios que presentan
- Cada revisión que se realiza el cliente analiza si hay avance o demora.
- El cliente aporta y reduce las iteraciones.

***Desventajas***
- El cliente esta involucrado en el transcurso del desarrollo y está consciente
de invertir los recursos para el proceso.
-  El cliente debe colaborar los valores y el enfoque de cómo abordar el
desarrollo
- Al trabajar directamente con el cliente no todo profesional puede verse
involucrado
---
### Prototipado
![Modelo propotipado](https://i.ytimg.com/vi/Ur2EstBKGPk/maxresdefault.jpg)

***Figura 3:Modelo en Propotipado***

Este método se usa tener mas o menos una idea de lo que va a hacer el sistema,
lo aplicamos cuando es rápido en el desarrollo.
Tiene un enfoque de desarrollo desechable (versión rudimentaria del
sistema que luego se lo desecha), evolutivo (el prototipo debe
convertirse en el sistema final) y mixto (combinación de prototipos
desechables y evolutivos).

### Incremental
![Modelo Incremental](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQtjAryZyv26ZPaqNtBRjqmCQs9uKpd0Bcfow&usqp=CAU)

***Figura 4:Modelo Incremental***


Este consiste en la iteracion de varios ciclos de vida en cascada y al final de cada iteracion se le entrega
al cliente una version mejorada y con nuevas funcionalidades.
El cliente es el encargado de revisar el producto y proponer nuevas mejoras, esto seguira hasta que el cliente este satisfecho.
### Incremental vs. Iterativo
El incremental y el iteratvo son parecidos, pero tienen esta gran diferencia.
- Desarrollo incremental: sistema parcial, funcionalidad completa
- Desarrollo iterativo: sistema completo; funcionalidad parcial

### Modelo en Espiral
![Modelo en espiral](https://aspgems.com/wp-content/uploads/2019/04/modelo-espiral.png)


***Figura 5:Modelo Espiral***

Es un modelo de proceso de software evolutivo, que proporciona el
potencial para el desarrollo rápido de versiones incrementales del
software
Este modelo  como se ve en la imagen el avance se realiza desde el centro hacia el exterior.

### Basado en Componentes
![Basado en Componentes](https://matriarm.files.wordpress.com/2009/12/untitled2.jpg?w=597&h=330)

***Figura 6:Desarrollo Basado en Componentes***

Un componente es una unidad ejecutable e independiente.
Para el desarrollo con reutilizaci´on debe ser posible encontrar los
componentes reutilizables apropiados.
Los componentes deben tener documentaci´on asociada para ayudar a
comprenderlos y adaptarlos a una nueva aplicación.

### Metodología Agil
![Metodología Agil](https://lh3.googleusercontent.com/gkslmVS7F0awJSuvQJ4EisFZIUtnAjJboenfmLZ6JOLi8yc2MAhB1YzbtKZlYBub73ULm7757uTcO4-I5efX1WkUPd0Hpx_5g3tXWG9S46qi3BFgfhBZXO0L90Y9iJOpVdUhL5A))

***Figura 7:Metodología Agil***

Las metodologias agiles son las mas usada hoy en dia y como se ve en la imagen prescinde de la documentación excesiva y pone mayor enfasis en la programación y en desarrolar el producto


### Agil:Scrum
![Scrum](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTdDjXvtK-MZ9cP58LVtiAT4I67fVVdDoMPVA&usqp=CAU)

***Figura 8:Scrum***

***Scrum*** es un proceso en el que se aplican de manera regular un conjunto de buenas prácticas para trabajar colaborativamente, en equipo, y obtener el mejor resultado posible de un proyecto. Estas prácticas se apoyan unas a otras y su selección tiene origen en un estudio de la manera de trabajar de equipos altamente productivos.
En Scrum se realizan entregas parciales y regulares del producto final, priorizadas por el beneficio que aportan al receptor del proyecto. Por ello, Scrum está especialmente indicado para proyectos en entornos complejos, donde se necesita obtener resultados pronto, donde los requisitos son cambiantes o poco definidos, donde la ***innovación***, la ***competitividad***, la ***flexibilidad*** y la ***productividad*** son fundamentales.

### Agil: XP(eXtreme Progamming)
![XP](https://github.com/xlindao/xlindao.github.io2/blob/master/ds.jpg)

***Figura 9:XP(eXtreme Programming)***

Extreme Programming (XP) es un marco de desarrollo de software ágil que tiene como objetivo producir software de mayor calidad y mayor calidad de vida para el equipo de desarrollo. XP es el más específico de los marcos ágiles con respecto a las prácticas de ingeniería adecuadas para el desarrollo de software.
Los cinco valores de XP son comunicación, simplicidad, retroalimentación, coraje y respeto.

---
