# Principios SOLID

Los principios **SOLID** son cinco reglas de diseño de software que ayudan a crear código más limpio, fácil de mantener y menos propenso a errores. Aquí te los explico de forma simple:

1. **S - Single Responsibility Principle (SRP)**  
   Cada clase o módulo debe tener una sola responsabilidad, es decir, una sola razón para cambiar. Esto hace que el código sea más fácil de entender y modificar sin afectar otras partes.

2. **O - Open/Closed Principle (OCP)**  
   El código debe estar **abierto para ser extendido** pero **cerrado para ser modificado**. Esto significa que puedes agregar nuevas funcionalidades sin cambiar el código existente, reduciendo el riesgo de errores.

3. **L - Liskov Substitution Principle (LSP)**  
   Las subclases deben poder usarse en lugar de sus clases base sin afectar la funcionalidad del programa. En otras palabras, una subclase debe comportarse como la clase de la que hereda.

4. **I - Interface Segregation Principle (ISP)**  
   Es mejor tener varias interfaces pequeñas y específicas que una interfaz grande y general. Esto permite que las clases solo implementen lo que realmente necesitan, manteniéndolas más simples y flexibles.

5. **D - Dependency Inversion Principle (DIP)**  
   Las clases deben depender de **abstracciones** y no de implementaciones concretas. Esto garantiza que los cambios en detalles específicos no afecten el diseño general del sistema.

---

---
title: Principios SOLID
markmap:
  colorFreezeLevel: 2
---

## **S - Single Responsibility Principle (SRP)**

### Definición

- Cada clase o módulo debe tener una única responsabilidad para mantener el código enfocado en una sola tarea.

### Beneficios

- **Mejor mantenibilidad**: Facilita la localización y corrección de errores, ya que cada clase tiene una función clara.
- **Reusabilidad incrementada**: Al tener clases enfocadas, es más fácil reutilizarlas en otros contextos o proyectos.
- **Facilidad para realizar pruebas unitarias**: Las clases con una sola responsabilidad son más fáciles de probar, ya que sus funciones están claramente definidas.
- **Escalabilidad del sistema**: Los cambios en una parte del código no afectan otras áreas, permitiendo expandir el sistema de forma ordenada.
- **Reducción de complejidad**: Al separar las responsabilidades, el código es más sencillo de leer y comprender.

### Cuándo Aplicar

- **Alta complejidad y difícil mantenimiento**: Si una clase tiene múltiples responsabilidades, el código se vuelve confuso y difícil de mantener.
- **Dificultad para realizar pruebas unitarias**: Las clases con varias funciones son complicadas de probar, ya que es difícil aislar los errores.
- **Duplicación de código**: Si encuentras que estás duplicando funcionalidad en diferentes partes, es probable que puedas refactorizar el código aplicando SRP.
