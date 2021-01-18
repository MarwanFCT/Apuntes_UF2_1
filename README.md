# Apuntes de Entornos de desarrollo UF2

### INDICE DEL TEMARIO

- *INTRODUCCIÓN*
- *PRUEBAS*
- *INTEGRACIÓN*
- *CALIDAD*


#### INTRODUCCIÓN

Esta unidad comprende todo lo que tiene que ver con mejorar la calidad de nuestro código mediante prácticas que son necesarias para un código impoluto, como seria conocer los tipos de pruebas que existen, cuales usar en cada caso y valorar la estructura de nuestro código.

Las pruebas tienen como finalidad identificar que es lo que funciona como queremos que funcione y lo que no va como se supone que debe ir. Para realizar estas pruebas se utilizan marcos de trabajo, que se podria resumir en una herramienta que reune unas utilidades como bibliotecas, herramientas y buenas practicas o suposiciones. Esto permite que el desarrollo en caso de ser en grupo pueda ser uniforme.

#### PRUEBAS

Las pruebas se pueden clasificar de varias maneras:

###### **Por la Forma**
- Hay pruebas dinámicas que te obligan a ejecutar la aplicación para poder realizarlas para poder medir su comportamiento.
- Hay pruebas estáticas, que al contrario de las anteriores, se pueden realizar sin ejecutar la aplicación, examinando el codigo fuente sin más.

-  **Por Estrategia**
- Caja Negra es una estrategia que se usa cuando lo que quieres probar es especificamente el funcionamiento correcto del programa o aplicación.
  Principalmente estudia el sistema desde fuera, se proporcionan entradas y se estudian las salidas del programa trabajando sobre la interfaz del mismo.
- Caja Blanca es una estrategia que se usa cuando deseas probar la estructura del codigo fuente y la eficiencia del mismo.
  Sobretodo examina el código fuente y la ejecución del programa.

-  **Por Tipo**
- Las Pruebas funcionales son las que ponen a prueba que el programa cumpla su proposito.
- Las pruebas no funcionales son las que ponen a prueba aspectos más extra, como la eficiencia, la seguridad o el rendimiento.

-  **Por Mecanismo**
- Existen los mecanismos manuales que significa que la prueba la realiza una persona humana revisando el codigo.
- Existen los mecanismos automáticos que significa que la prueba es realizada por un software o maquina que ejecuta el codigo revisando el resultado del mismo, con el que se esperaba obtener.

#### INTEGRACIÓN

#### CALIDAD
