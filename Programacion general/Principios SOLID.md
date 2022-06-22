Principios de programación SOLID

	Objetivo: Escribir mejor el código 
			  Código mas mantenible
			  Fácil de cambiar
			  Se extensible los proyectos
			  
- Single responsability (SRP)
- Open-Close principle (
- Liskov substitution (LS)
- Interface segregation principle (ISP)
- Dependecy inversion principle


 - Single responsability:
	Cada clase debe tener una responsabilidad unica y bien definida. No tener una clase que tengas todas las responsabilidades de los procesos.
	
 - Open-Close: 
	Una clase debe estar abierta para su extensión pero cerrada para su modificación, esto normalmente lo podemos lograr usando herencia, polimorfismo o interfaces.
	
 - Liskov substitution: 
	Una subclase puede ser sustituida por su superclase. Podemos crear una subclase llamada Auto, la cual deriva de la superclase Vehiculo.
	
 - Interface segregation principle:
	Establece que los clientes no deben ser forzados a depender de interfaces que no utilizan.
	Tener clases pequeñas especificas.
	Es importante que cada clase implemente las interfaces que va a usar.
	
 - Dependecy inversion principle:
	Establece que los modulos de alto nivel no deben depender de los de bajo nivel. Se debe depender de las abstracciones(Interfaces). 
	Tener interfaces que seran las encargadas de hacer la dependencias.
	