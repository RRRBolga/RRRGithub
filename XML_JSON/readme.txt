Ejercicio XML:

Crea un archivo XML que represente la información de algunos libros. 
Cada libro debe tener un título, un autor y un año de publicación. Puedes incluir al menos tres libros en tu archivo.

Solución:

Puedes encontrar la solución en el fichero library.xml

Esta es una estructura XML simple que contiene información sobre tres libros diferentes. 
Cada libro está representado como un elemento <book>, que contiene subelementos para el título, el autor y el año de publicación. 
Se ha añadido un atributo id al elemento <book> para identificar de forma única cada libro.
El elemento raíz es <library>, que contiene todos los libros.

-----------------------------------------------------------------

Ejercicio XSD:

Crea un archivo XSD que sirva para validar el XML anterior.

Solución:

Puedes encontrar la solución en el fichero library-schema.xsd

En este ejemplo, el XML hace referencia al esquema XSD mediante el atributo xsi:noNamespaceSchemaLocation. 
El esquema define la estructura permitida del XML, especificando que el elemento raíz <library> debe contener uno o más elementos <book>, 
y que cada <book> debe contener elementos <title>, <author> y <year>, además del atributo id que es requerido y debe ser de tipo xs:ID.
Este tipo ID est un tipo especial que se suele usar como un identificador. En el caso de XML y XSD, por convenio, NO debe empezar por un dígito.
Los elementos <title>, <author> y <year> tienen tipos de datos específicos definidos por el XML Schema (XSD).
En este caso, corresponden a string, string e integer, respectivamente.

-----------------------------------------------------------------

Ejercicio JSON:

Convierte el XML del ejercicio 1 a formato JSON y crea un esquema que lo valide.

Solución:

Puedes encontrar la solución en el fichero library.json y library-schema.json

-----------------------------------------------------------------

Validación XML:

https://www.xmlvalidation.com/

Validación JSON:

https://jsonlint.com/