<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
<br>
  <h1 align="center">Metodos en Java 👨‍💻</h1>
  <h2 align="left"> 📙 | Introduccion a metodos en Java</h2>
  <p align="left">
En Java, los métodos son bloques de código que realizan tareas específicas y pueden ser reutilizados a lo largo del programa. Representan una forma tradicional y estructurada de organizar la lógica, facilitando la modularidad y el mantenimiento del código. Un método en Java se define con un nombre, un tipo de retorno, y puede recibir parámetros para operar sobre datos de entrada.

El uso adecuado de los métodos permite encapsular comportamientos, promover la reutilización y mejorar la legibilidad del código, valores que han sido pilares fundamentales en el desarrollo de software desde sus orígenes. Además, los métodos en Java pueden clasificarse en estáticos o de instancia, dependiendo de si pertenecen a la clase o a un objeto en particular, lo que ofrece flexibilidad para diseñar sistemas robustos y bien estructurados.
  </p>
  
<h2 align="left"> 🔎📄 | Explicacion de metodos Java</h2>
<p align="justify">
Un método en Java es un conjunto de instrucciones que se agrupan para realizar una tarea concreta dentro de un programa. La creación y uso de métodos es una práctica tradicional en la programación estructurada y orientada a objetos, pues facilita la organización y reutilización del código, valores que se han mantenido vigentes con el paso del tiempo.
</p>
<h3 align="left"> 🤔 | Parte de metodos Java</h3>
<p align="left">
    Un método típico en Java consta de los siguientes elementos:
</p>
   <details>
  <summary>Modificador de acceso</summary>
  <p align="left">Define la visibilidad del método por ejemplo <code>public</code> <code>private</code></p>
  
  <details>
    <summary align="center">ver mas</summary>
    <p align="star"><code>public</code> permite el acceso desde cualquier clase, mientras que <code>private</code> restringe su uso únicamente dentro de la misma clase.</p>
  </details>
</details>

<details>
    <summary>Tipo de retorno</summary>
    <p align="left">Indica el tipo de dato que el método devolverá al finalizar su ejecución. Puede ser un tipo <code>primitivo</code>, un <code>objeto</code> o <code>void</code> si no devuelve ningún valor.</p>
    <details>
        <summary align="center">ver mas</summary>
        <p align="star"> el tipo de dato que el método devolverá tras su ejecución, pudiendo ser tipos primitivos <code>int</code> <code>boolean</code>  objetos o void si             no retorna ningún valor</p>
    </details>
</details>

<details>
    <summary>Nombre de metodo con su union del proceso</summary>
    <p align="star">Debe seguir igual al proceso que se hara si es un menu entonces debe llamarse menu</p>
    <div align="center">
        <pre>
            <code align="center">
                public static void menu(){
                // logica para el menu
                }
            }
             y se llama en el main con menu();
            </code>
        </pre>
    </div>
</details>
<details>
  <summary>Tipo de retorno</summary>
  <p align="left">
    Indica el tipo de dato que el método devolverá al finalizar su ejecución. Puede ser un tipo <code>primitivo</code>, un <code>objeto</code> o <code>void</code> si no devuelve ningún valor.
  </p>
  <details>
    <summary align="center">ver más</summary>
    <p align="left">
      El tipo de retorno es esencial para determinar qué tipo de resultado ofrece un método. Java es un lenguaje fuertemente tipado, por lo tanto, todo método que no sea <code>void</code> debe devolver obligatoriamente un valor del tipo declarado.<br><br>
      Ejemplos de tipos primitivos: <code>int</code>, <code>double</code>, <code>char</code>, <code>boolean</code>.<br>
      También se puede retornar un objeto, como una instancia de una clase personalizada, por ejemplo <code>Persona</code>, <code>String</code> o una colección como <code>List&lt;String&gt;</code>.<br>
      El tipo <code>void</code> indica que el método no devuelve ningún valor.
    </p>
  </details>
</details>

<details>
  <summary>Parámetros (opcionales)</summary>
  <p align="left">
    Valores que el método recibe para operar. Los parámetros permiten que un método trabaje con información que le es pasada desde el exterior.
  </p>
  <details>
    <summary align="center">ver más</summary>
    <p align="left">
      Los parámetros son variables que se declaran entre los paréntesis del encabezado del método. Cada parámetro tiene un tipo de dato y un nombre, separados por comas si hay más de uno.<br><br>
      Por ejemplo: <code>public int sumar(int a, int b)</code><br>
      Aquí, <code>a</code> y <code>b</code> son parámetros de tipo <code>int</code>.<br>
      Los métodos también pueden no tener parámetros, y en ese caso se escriben los paréntesis vacíos <code>()</code>.
    </p>
  </details>
</details>

<details>
  <summary>Cuerpo del método</summary>
  <p align="left">
    Contiene las instrucciones que se ejecutan cuando el método es llamado. Está delimitado por llaves <code>{ }</code>.
  </p>
  <details>
    <summary align="center">ver más</summary>
    <p align="left">
      El cuerpo del método es el bloque donde se define la lógica que el método ejecutará. Aquí se colocan las sentencias necesarias para realizar la tarea que se espera del método: operaciones, condiciones, bucles, llamadas a otros métodos, etc.<br><br>
      Ejemplo:<br>
        <pre>
      <code>
        public int cuadrado(int x) {<br>
        &nbsp;&nbsp;&nbsp;&nbsp;return x * x;<br>
        }
      </code>
        </pre>
    <br><br>
      En este caso, el cuerpo contiene una única instrucción: retornar el cuadrado del número recibido.
    </p>
  </details>
</details>






</br>



</body>
</html>
