## 5.1.3. Source Code Style Guide & Conventions.
Para el desarrollo de la parte de HTML y CSS se utlizara Google HTML/Css Style Guide, ya que contiene las convenciones que se deben tener en cuenta al trabajar cpnn dichas tecnologías. Para guirarnos de las buenas practicas accederemos mediante este enlace: https://google.github.io/styleguide/htmlcssguide.html. Entre algunas convenciones podemos mencionar:

### HTML y CSS:


- **Declaración del tipo de documento:** Siempre declarar el tipo de documento con `<!DOCTYPE html>`.
- **Nombres de elementos en minúsculas:** Utilizar siempre letras en minúsculas para los nombres de los elementos HTML como `<p>`, `<h1>`, `<section>`, entre otros.
- **Cierre de elementos HTML:** Cerrar siempre los elementos HTML, por ejemplo, `<p></p>`.
- **Comillas en atributos:** Siempre poner entre comillas los atributos dentro de un elemento HTML, como `<p class="name"></p>`.
- **Atributos para imágenes:** Especificar `alt`, `width`, y `height` para imágenes.
- **Espaciado y formato estandarizado:** Mantener un espaciado y un formato de código consistentes.
- **Evitar líneas de código extensas:** Dividir el código en líneas más cortas para facilitar la lectura.
- **Uso de etiquetas meta:** Utilizar meta tags al inicio y asegurarse de incluir el elemento `<title></title>`.


  ### JavaScript:
Para el lenguaje JavaScript, se seguirá la guía de estilo proporcionada por Google en el repositorio de GitHub  [ https://google.github.io/styleguide/jsguide.html ]. Algunas de las convenciones incluyen:

-	Nomenclatura en camelCase: Nombrar variables y funciones utilizando camelCase, por ejemplo, numberArray.
-	Comillas simples: Utilizar comillas simples para strings, como const message = 'This is a string';.
-	Uso de punto y coma: Agregar un punto y coma al final de cada sentencia.
-	Uso de let o const: Evitar declarar variables con var y en su lugar utilizar let o const.
-	Espaciado y formato de código: Mantener un formato de código claro y espaciado adecuado.
-	Manejo de errores: Implementar manejo de errores y excepciones de forma apropiada.
-	Comentarios y documentación: Utilizar comentarios y documentación de código según sea necesario.
### Gherkin (Archivos .feature):

Para el lenguaje Gherkin, se seguirán las convenciones mencionadas en "Make your Gherkin Specifications More Readable" para escribir especificaciones claras y legibles. Se puede conocer más sobre la forma de escribir en el lenguaje de Gerkhin mediante el siguiente enlace: https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/ .  A continuación, algunas de las convenciones incluyen:

-	Lenguaje simple: Escribir especificaciones en un lenguaje simple y fácil de entender.
-	Palabras clave Given/When/Then/And: Utilizar las palabras clave Given, When, Then, y And para los pasos del escenario.
-	Verbos finitos: Usar verbos finitos para describir acciones en los escenarios.
-	Evitar redundancias: Evitar redundancias en la descripción de los pasos en el escenario.
-	Formato consistente: Mantener un formato y estilo consistentes en toda la especificación.

### Vue.js:
Para el desarrollo con Vue JS se tiene como referencia las convenciones ya definidas por el mismo equipo de Vue con el objetivo de mantener un formato entendible y que ayude en el mantenimiento del sistema. Se puede visualizar las convenciones en el siguiente enlace: https://v2.vuejs.org/v2/style-guide/?redirect=true . a continuación se presentan algunas convenciones en Vue JS:

-	Nombres de componentes deben tener múltiples palabras.
-	El componente data debe ser una función que retorne valores.
-	Detalles de propiedades deben estar definidos.
-	Usar key con v-for.
-	Evitar mezclar v-if con v-for en un mismo scope.


### C#:
Para el uso de C# Microsoft provee una quia de estilos bastante completa cual nos permitirá aplicar estándares aplicados por Microsoft. Se puede conocer mas sobre esto en el siguiente link: https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions  . entre algunas convenciones podemos mencionar:
-	Se utiliza PascalCase para nombrar clases, estructuras o registros.
-	Los parámetros se nombran en camelCase.
-	Los comentarios se escriben en líneas separadas y se evita el exceso de comentarios.
-	Se respeta el espaciado después de comas y operadores.
-	Las llaves deben ir en una línea nueva al declarar una clase, estructura, entre otros

### .NET Framework:
Finalmente, para .NET Framework también Microsoft provee una guía de estilos bastante completa as cuales abarcan varias nociones involucradas en el uso de este framework. Se puede acceder a la guía desde el siguiente enlace: https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines . A continuación, se mencionan algunas convenciones:

-	Se siguen las guías de estilo de Microsoft para .NET Framework.
-	Los archivos deben incluir los comentarios de licencia de .NET.
-	Se evita el uso de this a menos que sea necesario.
-	Se especifica la visibilidad de los miembros (por ejemplo, private).
-	Las llaves se colocan en una nueva línea separada del código.
-	Se emplea espaciado después de comas y operadores.






