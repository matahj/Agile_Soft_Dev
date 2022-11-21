## Sesión 03. Niveles de Software Testing.

En la sesión 03 se revisaron:

* Los niveles de software testing (componente o unitarias, integración, sistema, aceptación), sus objetivos, responsabilidades y actividades.
* Los objetivos del "Test Driven Development" y sus ventajas.

En este *work*: (1).-Se desarrollan pruebas a nivel componente e integración en código ya existente. (2).-Se pone en práctica el Desarrollo de Software conducido por Pruebas (TDD).

1. Se formulan algunas pruebas unitarias sobre la clase PizzaOrden.java utilizando el framework de pruebas TestNG en Eclipse.

- [ ] Implementación.
- [ ] Video.


2.-Se implementa un sistema de puntuación (clase SistemaLealtad.java) utilizando TestNG y TDD en Eclipse.

- [ ] Implementación.
- [ ] Video.

### Configuración de las clases de prueba.
1. Crear la clase PizzaOrden.java
2. Crear la clase TestPizzaOrden.java con un método de prueba.

~~~
@Test
public void testMethod() {
	System.out.println("Testing Method");
}
~~~
3. Con el cursor sobre @Test agregar la "TestNG Library"
4. importar "test org.testng.annotations.Test"
5. Ejecutar la clase como "TestNG Test" 


