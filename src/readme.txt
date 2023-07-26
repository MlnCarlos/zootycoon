- ¿Cuántas clases tiene el proyecto?
R// 3

- ¿En cuál clase se define el programa principal?
R// Zoologico

- ¿Cuántos objetos de la clase Animal se crean en la clase principal?
R// 2

- ¿Cuántos y cuáles son los atributos de la clase Animal?
R// 4 ,    protected String nombre;
           protected String genero;
           protected double peso;
           protected Animal pareja;

- ¿Cuáles atributos de la clase Animal no son primitivos?
R// Son:     protected String nombre;
             protected String genero;
             protected Animal pareja;

- ¿Qué pasa si eliminamos la línea 17 de la clase Zoologico?
R// Al eliminar la linea 17 ( animal1.encontrarPareja(animal2); //Un animal consigue pareja ) no podriamos ejecutar el
metodo encontrarPareja y nos arrojaria una exepcion en donde nos indica que estamos eliminando el emparejamiento y por ende
el atributo pareja seguiria siendo NULL y no podrian tener hijos

- ¿Cuántos métodos tiene la clase Familia?
R// 2, tenerHijo(String nombre) y imprimirFamilia()

-¿Cuántos parámetros tiene el método tenerHijo() de la clase Familia?
R// Tiene 1 parametro, String nombre

- ¿Cuántos atributos inicializa el constructor de la clase Familia?
R// Inicializa 2 atributos, public Familia(Animal papa, Animal mama)

- ¿Qué tipo de retorno tiene el método tenerHijo()?
R// retorno Void.