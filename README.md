# PREPROCESADORES DE CSS  

## PUG

Pug es un generador de templates implementado con Javascript que nos permite escribir un pseudocódigo limpio y fácil de leer que será compilado a HTML.

- Las variables no vienen de forma nativa en HTML pero con PUG podemos usarlas. En ellas almacenamos datos y los reutilizarlos en todo nuestro archivo HTML evitándonos tener que escribir lo mismo una y otra vez.

- Un condicional nos permite evaluar cierta condición y bifurcar entre dos caminos dependiendo de si se cumple o no.

- Un loop es un fragmento de código que va a ejecutar de forma repetitiva hasta que cumpla una condición.

- Los includes sirven para incluir un archivo de extensión *.pug dentro de otro.

- Los extends te permiten adicionar bloques de código a una página.

## LESS

Less es un preprocesador para CSS que nos permite trabajar hojas de estilo con funcionalidades de un lenguaje de programación.

- En las variables almacenamos datos que se puede reutilizar en todas nuestras hojas de estilos. Así evitamos tener que escribir lo mismo una y otra vez cuando se realiza algún cambio, ya que sólo vamos a modificar el valor de la variable y se aplicará a todos los lugares donde sea usada.

- Comúnmente almacenamos en variables las guías de estilo de nuestro sitio, como pueden ser los colores y fuentes.

- La diferencia entre mixins y funciones es que las funciones por general hacen cálculos y regresan un resultado que es usado como valor de alguna propiedad.

Las funciones en Less ya están prediseñadas.

- Con los mixins logramos escribir menos código, produciendo un código más claro, más expresivo y sobre todo más fácil de mantener.
Su finalidad es ofrecer una funcionalidad que pueda ser reutilizada en otras clases pero que no está pensada para usarse de forma autónoma. Nos permite crear bloques reusables de código que cambian su resultado dependiendo del parámetro que enviemos.

## SASS

Sass (Syntactically Awesome StyleSheets) es una extensión de CSS que añade características muy potentes y elegantes a este lenguaje de estilos.

Sass es basado en Ruby a diferencia de Less y Stylus que se basan en Javascript.

- En las variables almacenamos datos que se puede reutilizar en todas nuestras hojas de estilos. Así evitamos tener que escribir lo mismo una y otra vez cuando se realiza algún cambio, ya que sólo vamos a modificar el valor de la variable y se aplicará a todos los lugares donde sea usada.

Comúnmente almacenamos en variables las guías de estilo de nuestro sitio, como pueden ser los colores y fuentes.

- Import nos permite escribir código modular separando en diferentes archivos para después importarlos todos en uno solo y tener una base código mucho más ordenada.

- Extends sirve para insertar los estilos de un selector en otro.

- La diferencia entre mixins y funciones es que las funciones por general hacen cálculos y regresan un resultado que es usado como valor de alguna propiedad.

## STYLUS

Es el preprocesador CSS más reciente de los tres. Fue creado por TJ Holowaychuk (ex programador de Node.js) y escrito en JADE y Node.js.