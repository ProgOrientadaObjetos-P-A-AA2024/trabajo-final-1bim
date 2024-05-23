## Trabajo Final del Primer Bimestre - Programación Orientada a Objetos

### Consideraciones Generales

- El trabajo es grupal.
- Se debe generar una solución en UML y lenguaje de programación en Java.
- Se debe crear un diagrama de clase por cada entidad. No realizar diagrama de la clase que contiene el método main. Considerar los paquetes.
- Se ha creado un proyecto de Netbeans, en el cual existen creados paquetes y clases; con base al proyecto seguir con el desarrollo de la solución.
- Usted debe adicionar las clases que sean necesarias.
- Las clases deben tener los métodos respectivos por cada atributo.
- Es importante usar métodos constructores en las clases.
- Usted debe crear una carpeta donde se ubican los diagramas de las clases.


### Problemática

Se necesita realizar un sistema de gestión de una inmobiliaria. En la empresa se necesita llevar el registro de constructoras, edificios, departamentos, casas

A continuación se definen algunas particularidades.
* Una casa tiene propiedades como: propietario (nombres, apellidos, identificación); precio por metro cuadrado; número de metros cuadrados; costo final; ciudad (nombre ciudad, nombre provincia); numero de cuartos.

* Por cada departamento se necesita: propietario (nombres, apellidos, identificación); precio por metro cuadrado; número de metros cuadrados; valor alícuota mensual; costo final; barrio (nombre del barrio, referencia); nombre de edificio; ubicación del departamento en edificio.


El sistema debe permitir ingresar: propietarios; barrio; ciudades; casas; departamentos. Además se solicita considerar lo siguiente:

* Todos los objetos de tipo propietario se deben ingresar y guardar en un archivo llamado **lospropietarios.dat**
* Todos los objetos de tipo barrio se deben ingresar y guardar en un archivo llamado **losbarrios.dat**
* Todos los objetos de tipo ciudad se deben ingresar y guardar en un archivo llamado **lasciudades.dat**
* Todos los objetos de tipo casa se deben ingresar y guardar en un archivo llamado **miscasas.dat**
* Para el ingreso de una **casa** se debe tomar en consideración el siguiente proceso:
	* El propietario se debe obtener del archivo lospropietarios.dat a través de la identificación.
	* La ciudad se debe obtener del archivo lasciudades.dat a través del nombre de la ciudad.
	* El costo final es igual a la operación de número de metros * precio del metro cuadrado + 3000.

* Todos los objetos de tipo departamento se deben ingresar y guardar en un archivo llamado departamentos.dat
* Para el ingreso de un **departamento** se debe tomar en consideración lo siguiente:
	* El propietario se debe obtener del archivo lospropietarios.dat a través de la identificación.
	* El barrio se debe obtener del archivo losbarrios.dat a través del nombre del barrio.
	* El costo final es igual al (número de metros * valor del metro cuadrado) + (valor alícuota mensual * 12) * 5.

* Debe existir la posibilidad de listar los datos ingresados para:
	* Propietarios
	* Barrios
	* Ciudades
	* Casas
	* Departamentos

### Herramientas a usar

- Lenguaje de programación Java
- Diagramador - DIAUML
- Git
- Github / GitHub-classroom

### Fecha de presentación

- Martes 4 de junio de 2024
