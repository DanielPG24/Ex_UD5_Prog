1. ¿Por qué ItemBiblioteca se ha definido como clase abstracta? 
Para que al poner un método abstracto no haya problemas ya que poner un abstracto en una clase no abstracto no se puede hacer.
2. Explica por qué la relación entre Libro y Autor es composición y no herencia. 
Es composición porque no se extienden las clases simplemente se usan la una a la otra, para que sea herencia deberia de haber un extends en la definicion de la clase. 
3. Indica dos ventajas de usar encapsulación en las clases del ejercicio. 
Que podemos definir con claridad los tipos de variables que tiene cada clase y que podemos darle la privacidad que deseemos para que el proyecto este seguro.
4. ¿Por qué ConfiguracionSistema podría declararse como final? 
Porque es algo que no queremos que se modifica ya que siempre va a hacer la misma función, por eso le ponemos el final.
5. ¿Qué ocurriría si el atributo contador de ContadorItems no fuera estático?

6. En qué situaciones es más adecuado utilizar herencia en lugar de composición. 

7. ¿Qué métodos importantes heredan todas las clases de Object? Menciona al menos 
tres. 

8. Explica brevemente el polimorfismo y cómo aparece en este ejercicio. 
El polimorfismo es cuando creas un metodo abstract para luego darle el cuerpo en otras clases como más adecuado sea, en este ejercicio lo vemos con el obtenerDescripcion, ya que el cuerpo se crea en las clases hijas y no en la padre.
9. Observa el siguiente método: 
public static void modificarTitulo(String titulo) { 
titulo = "Nuevo título"; 
} 
y la llamada: 
String t = "Java"; 
modificarTitulo(t); 
System.out.println(t); 
1. ¿Qué se imprimirá? 
2. Explica por qué ocurre esto en Java.

9.1. Lo que se imprime seria: 
Nuevo titulo
Java 
Ya que el system tiene como parámetro t y el metodo siempre va a hacer lo mismo porque es static, lo que significa que no va a dar otra respuesta que no sea la que tiene dada.

9.2. Es debido a que al darle un valor a la variable t y esta variable pasarla al metodo y al system, automaticamente leen Java ambos, pero como el metodo esta configurado de esta manera no le importa el valor del titulo, solo necesita que le sea pasada la variable para funcionar.
