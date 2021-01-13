# Resources

## YouTube

[Academind](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w)
[Dev Ed](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q)
[Fireship](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA)
[freeCodeCamp.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
[Web Dev Simplified](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)

## Blogs

[Smashing Magazine](https://www.smashingmagazine.com/)
[Free Code Camp](https://www.freecodecamp.org/news/tag/blog/)
[CSS-Tricks](https://css-tricks.com/)
[DEV Community 👩‍💻👨‍💻](https://dev.to/)
[Alligator.io](https://alligator.io/)
[SitePoint Blog](https://www.sitepoint.com/blog/)

## Newsletter

[CSS Weekly](https://css-weekly.com/)
[JavaScript Weekly](https://javascriptweekly.com/)
[Frontend Focus](https://frontendfoc.us/)

## Documentation

[MDN Web Docs](https://developer.mozilla.org/en-US/)
[Express](https://expressjs.com/)
[Mongoose](https://mongoosejs.com/)
[Sequelize](https://sequelize.org/master/index.html)
[Socket.IO](https://socket.io/)
[React](https://reactjs.org/)
[Redux](https://redux.js.org/)
[Jest](https://jestjs.io/en/)

## Apps

[Feedly](https://feedly.com/)

## Interviews

### Febrero 20

1. ¿Cuál es la diferencia entre usar == y ===?
   == compara valor, mientras que === compara también tipo
2. ¿Cuál es la diferencia entre var, let y const?
   CONST: Es una constante la cual NO cambiara su valor en ningún momento en el futuro. 
   VAR: Es una variable que SI puede cambiar su valor y su scope es local. 
   LET: Es una variable que también podra cambiar su valor, pero solo vivirá(Funcionara) en el bloque donde fue declarada.
3. ¿Qué es implicit coercion?
   Coercion is the process of conversion of data from one type to another

### Febrero 27

1. ¿En CSS qué es especificidad y cuáles son las reglas para determinarla?
   Especificidad es la manera mediante la cual los navegadores deciden qué valores de una propiedad CSS son más relevantes para un elemento
   Selectores de tipo (p.e., h1) y pseudo-elementos (p.e., ::before).
   Selectores de clase (p.e., .example), selectores de atributos (p.e., [type="radio"]) y pseudo-clases (p.e., :hover).
   Selectores de ID (p.e., #example).

2. ¿Qué es un closure?
   Una clausura o closure es una función que guarda referencias del estado adyacente (ámbito léxico). En otras palabras, una clausura permite     acceder al ámbito de una función exterior desde una función interior. En JavaScript, las clausuras se crean cada vez que una función es         creada.
   function iniciar() {
      var nombre = "Mozilla"; // La variable nombre es una variable local creada por iniciar.
      function mostrarNombre() { // La función mostrarNombre es una función interna, una clausura.
         alert(nombre); // Usa una variable declarada en la función externa.
      }
      mostrarNombre();
   }

3. ¿Qué es una pseudo-clase?
   Una pseudoclase CSS es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado. Por       ejemplo, :hover aplicará un estilo cuando el usuario haga hover sobre el elemento especificado por el selector.

### Marzo 5

1. ¿En JS, qué es un efecto secundario o un side effect?
   Side effects are the easier concept. A "pure function" is a function that maps its input value(s) into an output value function plus(x, y) {    return x + y; }. A "side effect" is any effect other than that return value. So, for instance:

   function plusWithSideEffects(x, y) { alert("This is a side effect");
   
   has the side effect of raising an alert dialog (and requiring user interaction).

2. ¿Qué es el HTML semántico y cuáles son algunos de sus beneficios?
   HTML nos brinda una serie de etiquetas con mayor significado, para cada parte, sección, o elemento de nuestra página, y que, aunque en la       práctica no generen un resultado distinto al de usar una etiqueta <div> como contenedor para todo, pueden darle mayor significado a nuestro     código
   Código más claro y fácil de mantener
   Ayuda a tu sitio a ser accesible
   Mejora tu posicionamiento SEO
   

    <article>
    <aside>
    <details>
    <figcaption>
    <figure>
    <footer>
    <header>
    <main>
    <mark>
    <nav>
    <section>
    <summary>
    <time>


3. ¿En HTML, cuál es la diferencia entre un elemento en linea y un elemento en bloque?
   Un elemento en línea ocupa sólo el espacio delimitado por las etiquetas que definen el elemento en línea.
   Un elemento en bloque ocupa todo el espacio de su elemento padre (contenedor)
4. ¿Cómo funciona la herencia de _Prototipos_ en JS?
   https://developer.mozilla.org/es/docs/Web/JavaScript/Herencia_y_la_cadena_de_protipos

### Marzo 12

1. ¿Qué es un pseudo-elemento?
   Al igual que las pseudo-classes, los pseudo-elementos se añaden a los selectores, pero en cambio, no describen un estado especial sino que,     permiten añadir estilos a una parte concreta del documento. Por ejemplo, el pseudoelemento ::first-line selecciona solo la primera línea del     elemento especificado por el selector.
2. ¿Qué es hoisting?
   una estricta definición de hoisting sugiere que las declaraciones de variables y funciones son físicamente movidas al comienzo del código
3. ¿Cuál es la diferencia entre un callback y una promesa?
    Una Promise (promesa en castellano) es un objeto que representa la terminación o el fracaso de una operación asíncrona. 
    Esencialmente, una promesa es un objeto devuelto al cuál se adjuntan funciones callback, en lugar de pasar callbacks a una función.
    Un callback (llamada de vuelta) es una función que recibe como argumento otra función y la ejecuta.
4. [count and say](https://leetcode.com/problems/count-and-say/)

### Marzo 19

1. ¿Qué es un middleware?
2. ¿Qué es el session storage?
   sessionStorage almacena información mientras la pestaña donde se esté utilizando siga abierta, una vez cerrada, la información se elimina.
3. ¿Qué es el package.json?
4. [Majority Element - LeetCode](https://leetcode.com/problems/majority-element/)

### Marzo 26

1. ¿Qué es una función pura?
   En programación, las Funciones Puras son aquellas que cumplen con dos requisitos básicos:

   Dado unos parámetros de entrada de idéntico valor, la función siempre devolverá el mismo resultado.
   El cómputo de la función, su lógica, no implica ningún efecto observable colateral fuera de ella. (side effect)

2. ¿Qué es el virtual DOM?
    DOM (cuyas siglas son “Document Object Model") 
    El Virtual DOM es una representación en memoria del DOM real que actúa de intermediario entre el estado de la aplicación y el DOM de la        interfaz gráfica que está viendo el usuario.
3. ¿Qué es un API?
   Una API (siglas de ‘Application Programming Interface’) es un conjunto de reglas (código) y especificaciones que las aplicaciones pueden        seguir para comunicarse entre ellas: sirviendo de interfaz entre programas diferentes de la misma manera en que la interfaz de usuario          facilita la interacción humano-software.
4. [Move Zeroes - LeetCode](https://leetcode.com/problems/move-zeroes/)

### Abril 2

1. ¿Qué es `Prop Drilling` y cómo se puede evitar?
2. ¿Qué es inmutabilidad y por qué es importante en React?
3. ¿Cuál es el ciclo de vida de un componente?
   una serie de funciones que se ejecutan en distintos momentos de la vida del componente y nos permiten realizar distintas acciones en estos momentos.
   El ciclo de vida se puede dividir en 3 fases, el montado, actualización y desmontado del componente. Estas fases a su vez se dividen en varios métodos que puede tener el componente.
   componentWillMount()
   render()
   componentDidMount()
   componentWillReceiveProps(nextProps)
   shouldComponentUpdate(nextProps, nextState)   
   componentDidUpdate(prevProps, prevState)
   componentWillUnmount()

Que es el Event loop, Call Stack, Programación Asíncrona, Callbacks
[Leer](https://medium.com/@_ferh97/nodejs-y-el-event-loop-21b33fea6b03)

leer  promises
      Async
      Docker
      ApiRest JSON

diferencia npm npx
NPM es un gestor de paquetes de Node.js cuyo objetivo es gestionar los paquetes y las dependencias. Significa que podemos determinar en un fichero los paquetes que necesitamos (package.json) y luego instalar las dependencias que hay en él (npm install).
NPX es una herramienta para ejecutar paquetes de Node y viene incluido en la instalación de NPM desde la versión 5.2.
NPX funciona de la siguiente manera:
    Comprueba si el paquete a ejecutar está instalado
    Si no está instalado lo instala
    Si está instalado lo ejecuta
Con el parámetro --no-install podemos indicarle a NPX que si el paquete no existe no lo instale.

Emacs5 vs Emacs6


