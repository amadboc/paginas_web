# CSS: Selectores #
https://developer.mozilla.org/es/docs/Web/CSS/Introducci%C3%B3n/Selectors

- selector de etiqueta (tag selector)
    p {
    font-size: 1.5rem;
    }

- selector de clase (class selector)
    En un documento HTML, los selectores de clase buscan un elemento basado en el contenido de su atributo class. El atributo class está definido como una lista de elementos separados por espacio, y uno de esos elementos debe coincidir exactamente con el nombre de clase dado en el selector.

    sintaxis: .classname { style properties }

- selector de id (id selector)
    en un documento HTML, los selectores de ID de CSS buscan un elemento basado en el contenido del atributo id. El atributo ID del elemento seleccionado debe coincidir exactamente con el valor dado en el selector.

    /* El elemento con id="demo" */
    #demo {
    border: red 2px solid;
    }
- selectores agrupados (,)

- selectores combinados 
    - selector de descendientes ( ) (descendent selector)
    - selector de hijo (>) (child selector)
    - selector de hermanos siguientes (~) (next sibling selector)
    - selector de hermanos adyancentes (+) (adjacent sibliing selector)

- selector de atributo []

-pseudoclases -> definidas de forma dinámica :hover, :visited

-pseudoelementos -> ::first-letter, ::first-line

-pseudoelementos con contenido -> ::after, ::before

-pseudoclases posicionales (jeráquicas) -> :nth-of-type(n), :nth-child(n)
n es un número, una palabra clave: odd/even/last-child, o una fórmula (2n o 2n+1)
nth-child (odd/even) -> pares (2n), impares (2n+1)

- selector universal: * {color:black;font-size:16px}

- pseudoclase :not(p)
:not (p) {color:black;font-size:16px}










































