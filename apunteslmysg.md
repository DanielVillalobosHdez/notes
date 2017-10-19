# LENGUAJE DE MARCAS Y SISTEMAS DE GESTION

## TEMA 1

* informatica.
	* infor --> información.
	* matica --> automatica.
	* tratamiento automatico de la información.
	* Este tratamiento sige el proceso del tratamiento informatico.

	* ENTRADA --> PROCESO --> SALIDA.

	* ENTRADA --> información que yo quiero modificar.
	* PROCESO --> Transformación aplicada a los datos de entrada.
	* SALIDA --> información ya modificada.

	* inferir --> con una entrada y salida, averiguar el proceso.

* Las operaciones de un proceso se agrupan por tipos según su función.

* El proceso de la información se realizan operaciones.
	* operaciones aritmeticas --> operaciones matematicas (+,-,*,/...).
	*operaciones relacionales --> comparación de dos magnitudes (<, >, >=, <=, !=, =).
	*operaciones de control de flujo --> deciden que y como se realiza una acción:
		* Condicionales.
		* Búcles --> hace algo X veces.

* Primitivas de ENTRADA y SALIDA (E/S).
	*LEER/ESCRIBIR

* Según sea la combinación de operaciones en el proceso, el proceso informático será de mayor o menor complejidad.

## 1.2 LENGUAJES DE PROGRAMACIÓN

* Especifican el conjunto de operaciones que es posible realizar sobre un dispositivo.

### 1.2.1 LENGUAJE DE MAQUINA

* Formada por 0 y 1 y determinan las operaciones posibles que se pueden realizar sobre un microprocesador concreto.
* Cada procesador contiene sus propias instruciones, los programas que se escriben en lenguaje de maquina (en adelante LM) para un procesador concreto soló son validos para ese entorno. Sí usar ese programa en otro microprocesador, hay que adaptar las instruciones del programa al conjunto de instruciones del nuevo microprocesador.
*El LM no es portable.

### 1.2.2 LENGUAJE ENSAMBLADOR

* Se pasa de utilizar 0 y 1 del LM a caracteres alfabéticos parecidos al lenguaje natural llamado nemóticos.
* Se caracteriza por:
	* Los programas en lenguaje esamblador (en adelante LE) son igual de largos que en LM.
	* Son facilmete revisables, comparado con LM.
	*Es propio de cada maquina y no son portables.
* Apartir del LE es necesario el uso de traductores.

### 1.2.3 LENGUAJES DE ALTO NIVEL

* Son lenguajes por encima del LM.
* Son independientes de la arquitectura del microprocesador en el que se ejecutan. Son lenguajes portables y compatibles en diferentes entornos de utilización.
* Se caracteriza por:
	* Son programas más cortos que en LE.
	* Al separarse del LM se necesita una herramienta externa que se encarge de realizar una traducción al LM, este tipo de herramientas se denominan traductores.

## 1.3 FASES DE ELABORACIÓN DE UN PROGRAMA

* ANÁLISIS --> DISEÑO --> CODIFICACIÓN --> EXPLOTACIÓN --> MANTENIMIENTO  

### 1.3.1 ANÁLISIS

* Se realiza ls toma de datos del problema. Si el sistema se realiza sobre las necesidades de un cliente, será necesaria la toma de datos con los usuarios implicados para poder especificar los proceso, los requerimientos, etc.
* SALIDA: Especificación de requerimientos (Qué debe hacer el programa).

### 1.3.2 DISEÑO

* Se diseña el sistema con una codificación lógica, que resuelva de manera concreta los requerimientos detectados en la fase de análisis. En esta fase, se generan varios diagramas que resulven los requerimientos desde diferentes puntos de vista.

### SALIDA DIAGRAMAS CON SOLUCIÓN DE LOS REQUERIMIENTOS (CÓMO)

* Diagrama Entidad/relación: solución desde el punto de vista de los datos. 
* Diagrama de flujo de datos: solución desde el punto de vista de los procesos y los datos.
* Diagramas de despliege: solución desde el punto de vista de la infraestructura.
* Diagramas de acción: solución desde el punto de vista de las instruciones.
* UML: metodología que define diferentes diagramas de manera unificada

### 1.3.3 CODIFICACIÓN

* traducción a lenguaje de programación de los diseños generados en la fase de diseño. Tambien se incluyen pruebas initarias y de integración con el sistema.

![diagrama de acción](./1.png diagrama de acción)

```
BECARIO
PROGRAMADOR JUNIOR
PROGRAMADIR JUNIOR 
```

### SALIDA: PROGRAMAS ESCRITOS EN UN LENGUAJE DE PROGRMACIÓN QUE RESUELVE LOS DIAGRAMAS PLATEADOS EN EL DISEÑO

### 1.3.34 EXPLOTACIÓN

* Implantación del sistema sobre el entorno de jecución real. Adaptando los programas a pruevas reales, masivas y de stress que comprueba el perfecto funcionamiento de los componentes en un entorno de explotación definitivos