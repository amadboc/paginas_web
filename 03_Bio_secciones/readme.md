https://www.w3.org/TR/2011/WD-html5-20110525/sections.html

Los elementos HTML según HTML5

## body ## 
Es el único que no puede estar duplicado, solo hay un body. El resto sí.

## h1 ... ##

## header ##

El elemento de HTML Header (<header>) representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, pero también otros elementos como un logo, una sección que aglutine secciones de encabezados, una formulario de búsqueda o cosas parecidas.

## nav ##

The HTML &lt;nav> element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes. 

Dentro va un menú, un menú es una lista de links. Puede ir dentro del header o justo seguido.

## article ##

El Elemento article de HTML (&lt;article>) representa una composición auto-contenida en un documento, página, una aplicación o en el sitio, que se destina a distribuir de forma independiente o reutilizable, por ejemplo, en la sindicación. Podría ser un mensaje en un foro, un artículo de una revista o un periódico, una entrada de blog, un comentario de un usuario, un widget interactivo o gadget, o cualquier otro elemento independiente del contenido. 
Sindicación=suscripción. 
Sería como las entradas en un blog, artículos en un periódico...

## section ##

El elemento de HTML section (&lt;section>) representa una sección genérica de un documento. Sirve para determinar qué contenido corresponde a qué parte de un esquema. Piensa en el esquema como en el índice de contenido de un libro; un tema común y subsecciones relacionadas.  Es, por lo tanto, una etiquéta semántica. Su funcionalidad principal es estructurar semánticamente un documento a la hora de ser representado por parte de un agente usuario. Por ejemplo, un agente de usuario que represente el documento en voz, podría exponer al usuario el índice de contenido por niveles para navegar rápidamente por las distintas partes.

Si es pequeño no tiene mucho sentido dividirlo en secciones. 

Los artículos pueden esta contenidos en las secciones y los secciones en los artículos. La diferencia con article es que article es autocontenido. Autocontenido quiere decir que por si mismo tiene sentido, el que lo lea sabe de lo que le estamos hablando. Section puede ser una parte de la información que puede no estar completa y por si sola no le da una información completa al que lo lee.

## aside ##

El Elemento HTML Aside (&lt;aside>) representa una sección de una página que consiste en contenido que está tangencialmente relacionado con el contenido que le rodea, que podría ser considerado independiente de ese contenido. Estas secciones son a menudo representadas como barras laterales o como inserciones y contienen una explicación al margen como una definición de glosario, elementos relacionados indirectamente, como publicidad, la biografía del autor, o en aplicaciones web, la información de perfil o enlaces a blogs relacionados.
Como las publicidades. Son cosas extras que no son el contenido básico de mi sitio,son solo complementos. Suelen ir a un lado como su propio nombre indica.

## footer ##

El Elemento HTML Footer (&lt;footer>) representa un pie de página para el contenido de sección más cercano o el elemento  raíz de sección (p.e, su ancestro mas cercano &lt;article>, &lt;aside>, &lt;nav>, &lt;section>,&lt;blockquote>, &lt;body>, &lt;details>, &lt;fieldset>, &lt;figure>, &lt;td>). Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados. No tiene por qué ir al final de la página.

## adress ##

El elemento HTML &lt;address> aporta información de contacto para su &lt;article> más cercano o ancestro &lt;body>; en el último caso lo aplica a todo el documento.


Los elementos según versiones más avanzadas de HTML5 (ahora estamos en 5.2)

## main ##

El elemento HTML &lt;main>  representa el contenido principal del &lt;body> de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).
Header, nav (cuando es un nav genérico), aside y footer no pueden ir dentro de main.
Define lo que cambia en una página según vas navegando. Cuaando navegas la parte de arriba de las webs (header) y lo de abajo:conócenos, ayuda, trabaja con nosotros... (footer) no cambia según tú vas tocando botones.

Es único, como body.
