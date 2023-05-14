# Preguntas técnicas JavaScript
## JavaScript
### Junior
1. ¿Qué es una promesa en Javascript y cómo funciona?
* Una promesa es un objeto que representa el resultado eventual de una operación asíncrona. Una promesa puede tener tres estados posibles: pendiente, resuelta o rechazada. Cuando una promesa se resuelve, se llama a una función de éxito que recibe los datos que se resolvieron y, si la promesa es rechazada, se llama a una función de fallo que recibe el motivo del rechazo.

2. ¿Cuál es la diferencia entre null y undefined en Javascript?
* En Javascript, null es un valor asignado a una variable que indica la ausencia de cualquier objeto o valor, mientras que undefined significa que una variable no ha sido asignada un valor. En otras palabras, null se utiliza específicamente para indicar que algo no existe, mientras que undefined se utiliza para indicar que algo no ha sido definido o asignado.

3. ¿Qué es el concepto de hoisting en Javascript?
* El concepto de hoisting en Javascript se refiere a cómo las declaraciones de variables y funciones son elevadas al principio de su ámbito actual. Esto significa que incluso si una variable o función se declara más adelante en el código, se puede acceder a ella antes de su declaración debido al proceso de hoisting.

4. ¿Qué son los closures en Javascript?
* Un closure en Javascript es una función que tiene acceso a variables en su ámbito externo, incluso después de que la función externa ha sido devuelta o terminada. Los closures son una forma poderosa de crear funciones y objetos reutilizables que pueden encapsular el estado y la lógica interna.

5. ¿Cómo se manejan los errores en Javascript?
* Los errores en Javascript se pueden manejar utilizando el bloque try-catch-finally. El bloque try contiene el código que puede generar una excepción, mientras que el bloque catch maneja la excepción y proporciona una respuesta adecuada. El bloque finally se ejecuta independientemente de si se produjo o no una excepción y se utiliza para ejecutar cualquier código que sea necesario después de la finalización del bloque try-catch.

6. ¿Qué es una función de flecha (arrow function) en Javascript y cuál es su sintaxis?
* Una función de flecha es una forma más concisa de escribir una función en Javascript. Se puede definir utilizando la sintaxis "(argumentos) => {cuerpo de la función}". Las funciones de flecha tienen una sintaxis más limpia y clara que las funciones regulares, y también tienen un comportamiento especial en cuanto a su alcance léxico.

7. ¿Qué es el alcance léxico en Javascript y cómo afecta el comportamiento de las funciones?
* El alcance léxico en Javascript se refiere a la forma en que se resuelven las referencias a variables en una función en función de su ubicación en el código. Esto significa que las funciones pueden acceder a las variables definidas en su ámbito externo, incluyendo la función que las contiene, y que las variables dentro de una función no son accesibles desde fuera de ella.

8. ¿Qué es el operador de propagación (spread operator) en Javascript y para qué se utiliza?
* El operador de propagación es un operador de sintaxis que se utiliza para expandir una expresión en varios elementos. Se utiliza en arrays, objetos y funciones y permite copiar todos los elementos de un array u objeto en un nuevo array u objeto, o pasar argumentos de una función a otra.

9. ¿Qué son los métodos de matriz en Javascript y cómo se utilizan?
* Los métodos de matriz en Javascript son funciones incorporadas que se utilizan para realizar operaciones en arrays. Algunos ejemplos de métodos de matriz incluyen map, filter, reduce y sort. Cada método tiene una funcionalidad específica y se utiliza para realizar operaciones en los elementos de un array de una manera más rápida y fácil.

10. ¿Qué son los módulos en Javascript y cómo se utilizan?
* Los módulos en Javascript son bloques de código que se pueden importar o exportar de un archivo a otro. Se utilizan para organizar el código en piezas más pequeñas y reutilizables y para mejorar la legibilidad y mantenibilidad del código. Los módulos se definen utilizando la sintaxis "export" y se pueden importar en otro archivo utilizando la sintaxis "import".

### Ssr
1. ¿Qué es una API REST y cuál es su importancia en el desarrollo de aplicaciones web?
* Una API REST es una interfaz de programación de aplicaciones basada en HTTP que permite a las aplicaciones web comunicarse entre sí de forma eficiente y escalable. Las API REST son importantes en el desarrollo de aplicaciones web porque permiten la integración de diferentes aplicaciones y servicios, lo que puede mejorar la funcionalidad y la eficiencia de la aplicación.

2. ¿Cuál es la diferencia entre un servidor y un cliente en el contexto del desarrollo web?
* En el contexto del desarrollo web, un servidor es un programa que proporciona servicios a través de la red a través de solicitudes HTTP, mientras que un cliente es un programa que envía solicitudes HTTP a un servidor y procesa las respuestas. En términos más simples, el servidor es la parte que proporciona el servicio, mientras que el cliente es la parte que lo utiliza.

3. ¿Qué es el patrón MVC (Modelo-Vista-Controlador) y cómo se utiliza en el desarrollo web?
*  El patrón MVC es un patrón de arquitectura de software que se utiliza en el desarrollo web para separar la lógica de presentación de la lógica de negocio. El modelo representa los datos y la lógica de negocio, la vista representa la interfaz de usuario y el controlador actúa como intermediario entre el modelo y la vista. El uso del patrón MVC puede mejorar la claridad y la estructura de la aplicación web.

4. ¿Cuál es la diferencia entre synchronous y asynchronous en Javascript y cuál es la importancia de conocer estas diferencias?
* En Javascript, synchronous se refiere a la ejecución de código de forma secuencial, mientras que asynchronous se refiere a la ejecución de código en paralelo y sin bloquear el hilo principal. Es importante conocer estas diferencias porque el uso de operaciones asíncronas en Javascript puede mejorar la eficiencia y la escalabilidad de la aplicación web.

5. ¿Qué es la integración continua (CI) y cuál es su importancia en el desarrollo de software?
* La integración continua es un proceso de desarrollo de software en el que se integran y se prueban los cambios de código de forma automática y regular. La importancia de la integración continua en el desarrollo de software radica en que permite detectar y corregir errores de forma más temprana y reducir el riesgo de conflictos en el código. Además, la integración continua puede mejorar la eficiencia del proceso de desarrollo y aumentar la calidad del software.

6. ¿Qué es el concepto de herencia en programación orientada a objetos (POO) y cómo se implementa en Javascript?
* La herencia en POO se refiere a la capacidad de una clase para heredar propiedades y métodos de otra clase. En Javascript, la herencia se implementa a través del uso de prototipos y se puede lograr mediante la creación de objetos que hereden propiedades y métodos de un objeto base.

7. ¿Qué es el patrón de diseño Singleton y en qué situaciones se puede utilizar en el desarrollo de software?
* El patrón de diseño Singleton se utiliza para garantizar que una clase tenga una única instancia y que esta instancia sea accesible en todo momento. Se puede utilizar en situaciones en las que se requiere una única instancia de una clase, como por ejemplo para gestionar una conexión a una base de datos.

8. ¿Qué son las pruebas unitarias y por qué son importantes en el desarrollo de software?
* Las pruebas unitarias son pruebas automatizadas que se realizan a nivel de código para asegurarse de que una unidad de software, como una función o método, funciona correctamente. Son importantes en el desarrollo de software porque pueden detectar errores de forma temprana y garantizar la calidad del código.

9. ¿Qué es el concepto de asincronía en el desarrollo de software y cómo se puede implementar en Javascript?
* En el desarrollo de software, la asincronía se refiere a la ejecución de operaciones de forma no secuencial y sin bloquear el hilo principal. En Javascript, se puede implementar la asincronía utilizando callbacks, promesas o async/await, lo que puede mejorar la eficiencia y la escalabilidad de la aplicación web.
10. ¿Qué es el patrón de diseño Factory y en qué situaciones se puede utilizar en el desarrollo de software?
* El patrón de diseño Factory se utiliza para crear objetos sin exponer la lógica de creación al cliente. Se puede utilizar en situaciones en las que se requiere la creación de objetos complejos o en situaciones en las que se necesitan objetos diferentes en función de ciertos parámetros. El uso del patrón Factory puede mejorar la modularidad y la reutilización del código.


## React
### Junior
1. ¿Qué es JSX en React y por qué es importante?
* JSX es una extensión de la sintaxis de JavaScript que permite escribir código HTML dentro del código de JavaScript. Es importante en React porque simplifica la creación de componentes de UI, lo que hace que el código sea más legible y fácil de mantener.

2. ¿Qué son los Hooks en React y para qué se utilizan?
* Los Hooks son una característica de React que permiten utilizar el estado y otros comportamientos de React en los componentes funcionales. Se utilizan para agregar características a los componentes sin tener que convertirlos a componentes de clase, lo que hace que el código sea más legible y fácil de mantener.

3. ¿Cómo se puede implementar el enrutamiento en una aplicación React?
* El enrutamiento en React se puede implementar utilizando librerías como React Router. React Router proporciona componentes como Router, Route y Link que se pueden utilizar para crear rutas y enlaces entre páginas.

4. ¿Qué son los componentes controlados en React y por qué son importantes?
* Los componentes controlados en React son componentes que toman su valor y estado de un componente padre. Son importantes porque permiten que el estado de un componente se sincronice con el estado del componente padre, lo que hace que el código sea más fácil de depurar y de mantener.

5. ¿Qué son las pruebas unitarias en React y cómo se pueden implementar?
* Las pruebas unitarias en React son pruebas que se realizan para asegurarse de que los componentes de React funcionen correctamente. Se pueden implementar utilizando herramientas como Jest y Enzyme, que permiten simular eventos de usuario, hacer pruebas de renderizado y asegurar que los componentes se comporten de acuerdo a lo esperado.

6. ¿Qué son los Higher-Order Components (HOC) en React y cómo se pueden utilizar?
* Los HOC son componentes de orden superior en React que toman un componente como entrada y devuelven un nuevo componente con una funcionalidad añadida. Se utilizan para reutilizar la lógica común en varios componentes y para encapsular la lógica de gestión de estado y props.

7. ¿Qué son las propiedades (props) en React y cómo se pueden pasar a los componentes?
* Las props en React son datos que se pasan de un componente padre a un componente hijo. Se pueden pasar como atributos de JSX al llamar al componente hijo y se pueden acceder dentro del componente hijo utilizando this.props.

8. ¿Qué es el patrón de diseño Container-Presentational y cómo se puede utilizar en React?
* El patrón Container-Presentational es un patrón de diseño en el que los componentes se dividen en dos categorías: componentes contenedor y componentes presentacionales. Los componentes contenedor son responsables de la lógica de negocio y de la gestión del estado, mientras que los componentes presentacionales son responsables de la presentación de datos. Se puede utilizar en React para separar las responsabilidades de los componentes y hacer que el código sea más modular y fácil de mantener.

9. ¿Qué es el ciclo de vida de un componente en React y cuáles son sus métodos principales?
* El ciclo de vida de un componente en React se refiere a la secuencia de eventos que ocurren desde que se crea el componente hasta que se destruye. Los métodos principales del ciclo de vida de un componente son: componentDidMount, componentDidUpdate, componentWillUnmount y render.

10. ¿Qué es la programación funcional y cómo se puede aplicar en React?
* La programación funcional es un paradigma de programación que se centra en las funciones puras y la composición de funciones para resolver problemas. Se puede aplicar en React utilizando componentes funcionales y los Hooks, que son funciones puras que pueden componerse para agregar comportamientos adicionales a los componentes.

### Ssr
1. ¿Cómo se puede mejorar el rendimiento de una aplicación React?
* Hay varias formas de mejorar el rendimiento de una aplicación React, incluyendo: optimizar la carga inicial, reducir el tamaño del paquete, utilizar la caché y la pre-carga, implementar lazy loading, y utilizar la técnica de renderizado del lado del servidor (SSR).

2. ¿Qué son los patrones de diseño en React y por qué son importantes?
* Los patrones de diseño en React son soluciones comunes a problemas recurrentes que se han identificado en el desarrollo de aplicaciones con React. Son importantes porque permiten que el código sea más modular, escalable y fácil de mantener, y ayudan a los desarrolladores a escribir código de alta calidad.

3. ¿Qué son los estilos en línea (inline styles) en React y cómo se pueden utilizar?
* Los estilos en línea en React son una forma de aplicar estilos a un componente utilizando objetos JavaScript. Se pueden utilizar para crear estilos dinámicos y personalizados para un componente y se pueden aplicar utilizando la propiedad style en JSX.

4. ¿Qué son las librerías y frameworks complementarios a React y cuáles son sus funciones?
* Las librerías y frameworks complementarios a React son herramientas que se utilizan para complementar las capacidades de React y mejorar la eficiencia del desarrollo. Algunos ejemplos son Redux para la gestión del estado global, React Router para la navegación entre páginas, y Material UI para la creación de componentes de UI predefinidos.

5. ¿Qué es la virtualización de lista (list virtualization) en React y por qué es importante para el rendimiento de la aplicación?
* La virtualización de lista en React es una técnica que se utiliza para optimizar el rendimiento de las aplicaciones que manejan grandes cantidades de datos. Permite que sólo se rendericen los elementos que son visibles en la ventana de visualización del usuario, lo que reduce el tiempo de carga y mejora la experiencia del usuario.

6. ¿Qué es React Fiber y por qué es importante?
* React Fiber es una reescritura del algoritmo de conciliación de React que mejora la capacidad de respuesta y el rendimiento de la aplicación. Es importante porque permite la renderización incremental, el manejo de tareas en segundo plano y el control granular de la prioridad de la actualización de los componentes.

7. ¿Qué son los Hooks de React y cómo se pueden utilizar para mejorar la eficiencia del código?
* Los Hooks de React son una característica introducida en la versión 16.8 que permite utilizar el estado y otras características de React en componentes funcionales. Se pueden utilizar para evitar el uso excesivo de clases, para compartir lógica entre componentes y para mejorar la modularidad del código.

8. ¿Qué es el patrón de diseño Render Props y cómo se puede utilizar en React?
* El patrón de diseño Render Props es una técnica que se utiliza para compartir código entre componentes en React. Consiste en pasar una función como prop a un componente hijo y utilizar esa función para renderizar contenido dentro del componente. Se puede utilizar para mejorar la reutilización de código y la flexibilidad en el diseño de componentes.

9. ¿Qué son las pruebas unitarias (unit tests) en React y por qué son importantes?
* Las pruebas unitarias en React son pruebas automatizadas que se utilizan para verificar que el código funciona correctamente y cumple con los requisitos específicos de la aplicación. Son importantes porque ayudan a los desarrolladores a detectar errores temprano, reducen el tiempo de depuración y mejoran la calidad del código.

10. ¿Qué es el server-side rendering (SSR) en React y por qué es importante?
* El server-side rendering en React es una técnica que se utiliza para renderizar la aplicación en el servidor en lugar del navegador del usuario. Es importante porque mejora el rendimiento de la aplicación al reducir el tiempo de carga y mejorar la experiencia del usuario, especialmente en conexiones de baja velocidad o dispositivos más antiguos.


## NodeJs
# Junior
1. ¿Qué es Node.js y por qué es importante?
* Node.js es un entorno de tiempo de ejecución (runtime) de JavaScript que permite a los desarrolladores crear aplicaciones del lado del servidor con JavaScript. Es importante porque proporciona una plataforma única y flexible para el desarrollo de aplicaciones, lo que permite a los desarrolladores utilizar las habilidades de JavaScript en ambos lados del servidor (frontend y backend).

2. ¿Qué son las funciones asíncronas (async/await) en Node.js y cómo se utilizan?
* Las funciones asíncronas son una forma de escribir código asincrónico en JavaScript de una manera más legible y sencilla. Permiten que una función se suspenda hasta que se complete una operación asíncrona, como una llamada a una API o una consulta a una base de datos. Se utilizan utilizando la palabra clave "async" antes de la declaración de la función y "await" antes de la llamada a una operación asíncrona.

3. ¿Qué es un stream en Node.js y cómo se puede utilizar?
* Un stream en Node.js es una secuencia de datos que se procesan en tiempo real en lugar de esperar a que se complete toda la entrada antes de procesarla. Los streams se pueden utilizar para manejar grandes cantidades de datos o para transmitir datos en tiempo real, como en una aplicación de chat. En Node.js, hay cuatro tipos de streams: Readable, Writable, Duplex y Transform.

4. ¿Qué es la gestión de dependencias en Node.js y cómo se puede utilizar NPM para manejarlas?
* La gestión de dependencias en Node.js se refiere a la forma en que las bibliotecas y los módulos externos se incluyen en una aplicación Node.js. NPM (Node Package Manager) es una herramienta que se utiliza para gestionar las dependencias de Node.js. Permite a los desarrolladores instalar, actualizar y eliminar paquetes de una manera fácil y eficiente, y proporciona una gran cantidad de paquetes disponibles en su repositorio oficial.

5. ¿Qué es la programación orientada a eventos en Node.js y cómo se puede utilizar para mejorar la eficiencia del código?
* La programación orientada a eventos en Node.js es una técnica que se utiliza para escribir código asíncrono que responde a eventos específicos. En lugar de esperar a que una operación asíncrona se complete antes de continuar con el siguiente código, el código se ejecuta en respuesta a un evento. Se puede utilizar para mejorar la eficiencia del código en aplicaciones que manejan una gran cantidad de solicitudes simultáneas, como en aplicaciones web o en tiempo real.

6. ¿Cómo manejas los errores en Node.js?
* Los errores son una parte importante del desarrollo en Node.js, y hay varias maneras de manejarlos. Una forma es usar el bloque try-catch para capturar errores. Otra forma es usar el método "callback" de Node.js para manejar errores. También se pueden utilizar bibliotecas de manejo de errores como "express-validator" o "joi" para validar y manejar errores en una aplicación.

7. ¿Qué es la arquitectura de microservicios en Node.js y cuáles son sus beneficios?
* La arquitectura de microservicios en Node.js es una técnica que implica dividir una aplicación en pequeños servicios independientes que se comunican entre sí mediante API. Los beneficios de esta arquitectura incluyen una mayor escalabilidad, mayor flexibilidad y capacidad de actualización, y una mayor resistencia a fallos.

8. ¿Qué es la promesa en Node.js y cómo se utiliza?
* Una promesa en Node.js es un objeto que representa un valor que puede no estar disponible de inmediato, pero que se espera que lo esté en el futuro. Las promesas se utilizan para manejar el código asincrónico de una manera más legible y sencilla. Las promesas tienen tres estados posibles: pendiente, cumplida y rechazada.

9. ¿Qué es la creación de prototipos de Node.js y cómo se puede utilizar?
* La creación de prototipos en Node.js es una técnica que se utiliza para desarrollar aplicaciones rápidamente mediante la creación de prototipos y el refinamiento iterativo. Se pueden utilizar herramientas de creación de prototipos como "nodemon" para reiniciar automáticamente la aplicación después de cada cambio en el código, lo que permite a los desarrolladores iterar rápidamente y ver los cambios en tiempo real.

10. ¿Qué es la sincronización de procesos en Node.js y cómo se puede utilizar?
* La sincronización de procesos en Node.js se refiere a la forma en que los procesos se comunican entre sí en una aplicación Node.js. Se puede utilizar la sincronización de procesos para compartir datos entre procesos o para coordinar la ejecución de múltiples procesos en una aplicación. Las herramientas de sincronización de procesos incluyen "cluster" y "child_process" en Node.js.

### Ssr
1. ¿Qué es la arquitectura MVC en Node.js y cómo se puede utilizar?
* La arquitectura MVC (Modelo-Vista-Controlador) es un patrón de diseño comúnmente utilizado en aplicaciones web, incluyendo aplicaciones Node.js. El modelo representa los datos de la aplicación, la vista representa la interfaz de usuario y el controlador maneja la lógica de la aplicación. Node.js ofrece varias bibliotecas para implementar la arquitectura MVC, como "Express" y "Sails".

2. ¿Cómo manejas la autenticación y la autorización en Node.js?
* La autenticación y la autorización son dos aspectos importantes de la seguridad en una aplicación web. Node.js ofrece varias bibliotecas para manejar estos aspectos, como "Passport" para la autenticación y "jsonwebtoken" para la autorización. Además, se pueden utilizar bases de datos de usuarios para almacenar y autenticar usuarios.

3. ¿Cómo manejas el manejo de archivos en Node.js?
* El manejo de archivos en Node.js se puede hacer utilizando las funciones integradas de Node.js, como "fs", que proporciona métodos para leer y escribir archivos. También hay bibliotecas de terceros que pueden simplificar el manejo de archivos, como "multer", que se utiliza para subir archivos.

4. ¿Cómo se puede optimizar el rendimiento de una aplicación Node.js?
* El rendimiento de una aplicación Node.js puede optimizarse de varias maneras, como la optimización del código, el uso de cachés y la implementación de técnicas de escalabilidad. También se puede utilizar herramientas de monitoreo para identificar cuellos de botella y mejorar el rendimiento.

5. ¿Cómo manejas la integración de bases de datos en Node.js?
* Node.js es compatible con una variedad de bases de datos, incluyendo MySQL, MongoDB y PostgreSQL. Para integrar una base de datos en una aplicación Node.js, se pueden utilizar bibliotecas de terceros como "Sequelize" para bases de datos relacionales y "Mongoose" para bases de datos NoSQL. También se pueden utilizar bibliotecas ORM (Mapeo Objeto-Relacional) para facilitar la interacción con la base de datos.

6. ¿Qué es una promesa en Node.js y cómo se utiliza?
* Una promesa en Node.js es un objeto que representa un valor que puede estar disponible ahora o en el futuro. Se utiliza para manejar operaciones asíncronas en Node.js. Las promesas tienen dos métodos principales: "then()", que se utiliza para manejar el resultado de una promesa, y "catch()", que se utiliza para manejar errores.

7. ¿Cómo manejas la concurrencia en Node.js?
* La concurrencia en Node.js se puede manejar utilizando la técnica de "event loop" que es la forma en que Node.js maneja las operaciones asíncronas. Además, Node.js ofrece la opción de utilizar "worker threads" que permiten ejecutar varias tareas en paralelo.

8. ¿Cómo se pueden crear y consumir API RESTful en Node.js?
* Para crear una API RESTful en Node.js, se puede utilizar una biblioteca como "Express" que permite crear rutas para diferentes endpoints. Para consumir una API RESTful en Node.js, se pueden utilizar bibliotecas como "Axios" o "Request" para realizar peticiones HTTP a un servidor.

9. ¿Cómo se puede implementar el caching en Node.js?
* El caching en Node.js se puede implementar utilizando diferentes técnicas, como el uso de cachés en memoria, el uso de cachés en disco y el uso de cachés en red. Algunas bibliotecas de Node.js que permiten implementar el caching son "node-cache" y "redis".

10. ¿Cómo se puede implementar la seguridad en una aplicación Node.js?
* La seguridad en una aplicación Node.js se puede implementar utilizando diferentes técnicas, como la validación de datos, la encriptación de contraseñas, el uso de HTTPS, la prevención de ataques XSS y CSRF, entre otras. Node.js ofrece diferentes bibliotecas que permiten implementar estas técnicas, como "Helmet" y "csurf".
