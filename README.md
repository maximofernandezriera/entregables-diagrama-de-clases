# Ejercicios entregables diagrama de clases

Además de los 2 ejercicios vistos en clase, resuelve estos supuestos:

## 1. Restaurante

Un restaurante necesita almacenar información teniendo en cuenta las siguientes premisas:

* Un cliente va a un restaurante y puede solicitar una o más órdenes de servicio. Se registra la mesa en la que se sienta y la cantidad de comensales.
* El cliente puede ordenar bebidas y platos.
* La orden debe registrar la hora y el mesero que le atiende.
* El pago tiene tres datos: un subtotal (lo consumido por el cliente), la propina y los impuestos por la venta realizada.
* Se debe calcular el total del pago.
* La orden se puede pagar en efectivo o con tarjeta de crédito. Si es con tarjeta de crédito se necesita saber el número de tarjeta, el tipo y el nombre de titular; también se calcula el cargo por el uso de la tarjeta.

Crea un diagrama de clases donde se represente esta información, con la cardinalidad entre clases. Incluye, si es necesario, getters, setters y/o constructores.

## 2. Biblioteca

Se	desea	modelar	el	funcionamiento	de	una	biblioteca	municipal.

Los	libros	se	organizan	según	la	temática:	libros	infantiles,	narrativa,	ensayo,	poesía,	etc. Cada	temática	se	encuentra	alojada	en	una	planta	de	la	biblioteca.

Además,	 se	 deben	 registrar	 los	 libros	 que	 se	 encuentran	 en	 la	 biblioteca.	Cada librocontará	con	un	identificador,	titulo,	autor, editorial;	por	cada	libro	puede	haber	más	de	un ejemplar	disponible	para	préstamo.

Por	 cada	 préstamo	 deberá	 almacenarse	 el	 ejemplar,	 la	 fecha	 de	 préstamo,	 la	 fecha de	entrega	 estimada	 y	 la	 real.	 El	 préstamo	máximo	 será	 de	 30	 días.	 Los	 lectores	 que no	entreguen	 el	 libro	 a	 tiempo	 tendrán	 penalización. Para	 aplicar esa penalización,	 la	biblioteca	 cuenta	 con	 una	 ficha	 por	 cada	 lector,	 con	 su	 número	 de	 identificación	 o pasaporte,	su	nombre	y	su	dirección	postal.	Para	fomentar	la	lectura,	los	empleados	de	la	biblioteca,	que	poseen	su	propia	identificación	como	tales,	pueden	llevar	libros	a	casa	por	un	plazo	mayor	que	los	usuarios	convencionales.

## 3. Arqueólogos

Crea	un	diagrama	de	clases	para	representar	la	información	siguiente:

* Un	proyecto	arqueológico	se	compone	habitualmente	de	una	serie	de	actuaciones.
* Para	desarrollar	el	proyecto	se	requieren	personas	que	pueden	asumir	uno	o	más	 roles	dentro	del	proyecto simultáneamente.
* Los	roles	a	su	vez	son	de	dos	tipos:	responsables	y	técnicos.	Por	tanto	una	persona podría	desempeñar	un	rol	de	responsable	y	otro de	técnico, tres roles	de	técnico, etc.
* Los	técnicos	tienen	asignada	una	o	más	actuaciones	del	proyecto.

No	es	necesario	que	detalles	los	atributos	de	las	clases;	lo	fundamental	es	que	definas	una buena	estructura	de	clases	y	relaciones.
