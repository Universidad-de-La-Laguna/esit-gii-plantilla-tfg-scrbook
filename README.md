# Memoria de trabajo fin de grado

Esta plantilla de memoria de trabajo fin de grado se basa en la clase `scrbook` del paquete [KOMA-Script](https://ctan.org/pkg/koma-script). Este paquete ofrece más flexibilidad en el diseño de documentos y opciones de personalización que las clases estándares de LaTeX.

## Versiones

La plantilla se puede utilizar fácilmente en Overleaf utilizando la versión publicada en la galería:

https://www.overleaf.com/latex/templates/ull-esit-gii-memoria-de-trabajo-de-fin-de-grado/djcchzsbgvvh

También se puede descargar la última versión de la plantilla directamente desde GitHub:

https://github.com/Universidad-de-La-Laguna/esit-gii-plantilla-tfg-scrbook

## LaTeX

La plantilla está prepara para ser usada con LuaLaTex como compilador por defecto y Biber para la gestión de las referencias bibliográficas. Es posible que también funcione con XeLaTeX, pero solo ha sido probada con LuaLaTex. Por eso, para generar este documento, **se recomienda configurar el editor de LaTeX para que use LuaLaTeX**.

La plantilla no funciona con pdfLaTex por el uso del paquete `fontspec` para gestionar las fuentes OpenType.

## Fuentes

Las fuentes usadas y que deben estar instaladas son:

 * [lmodern](https://ctan.org/pkg/lm) — Latin Modern
 * [sourcecodepro](https://ctan.org/pkg/sourcecodepro) — Source Code Pro

## Paquetes incluidos

Entre otros, la plantilla incluye los siguientes paquetes que pueden ser útiles en la elaboración de la memoria

### Código

 * [algpseudocodex](https://ctan.org/pkg/algpseudocodex) — Proporciona entornos avanzados para describir algoritmos. Permite escribir pseudocódigo con numeración y resaltado.

 * [listings](https://ctan.org/pkg/listings) — Proporciona un entorno para incluir código fuente con resaltado de sintaxis.

### Figuras

 * [graphicx](https://ctan.org/pkg/graphicx) — Permite redimensionar, rotar y recortar imágenes fácilmente.

 * [pdflscape](https://ctan.org/pkg/pdflscape) — Permite crear páginas en modo apaisado en documentos PDF. Es útil para tablas o figuras anchas que necesitan más espacio horizontal.

 * [rotating](https://ctan.org/pkg/rotating) — Permite rotar objetos como tablas y figuras. Es útil para mostrar contenido en orientación vertical u horizontal.

### Tablas

 * [array](https://ctan.org/pkg/array) — Permite la definición de nuevos tipos de columnas y estilos de alineación en tablas. Mejora la personalización y el formato de tablas en LaTeX.

 * [booktabs](https://ctan.org/pkg/booktabs) — Facilita la creación de tablas de alta calidad. Proporciona comandos para líneas horizontales de diferentes grosores y espacios adecuados entre filas.
 
 * [longtable](https://ctan.org/pkg/longtable) — Proporciona un entorno para crear tablas que pueden abarcar múltiples páginas. Ideal para tablas extensas que no caben en una sola página.

 * [multirow](https://ctan.org/pkg/multirow) Permite crear celdas en tablas que abarcan múltiples filas. Útil para crear tablas más complejas.

 * [tabularx](https://ctan.org/pkg/tabularx) — Extiende el entorno tabular con soporte para ancho de columna automático. Permite crear tablas que se ajustan al ancho total de la página.

### Estilos

 * [caption](https://ctan.org/pkg/caption) — Proporciona opciones avanzadas para personalizar las leyendas de figuras y tablas. Permite cambiar el estilo, formato y posición de las leyendas.

 * [enumitem](https://ctan.org/pkg/enumitem) — Extiende las listas enumeradas y no enumeradas con opciones adicionales. Permite personalizar la numeración, el formato y el espaciado de listas.

 * [subcaption](https://ctan.org/pkg/subcaption) — Proporciona soporte para subtítulos en subfiguras y subtablas. Facilita la creación de figuras y tablas compuestas con leyendas individuales.

### Otros

 * [csquotes](https://ctan.org/pkg/csquotes) — Proporciona comandos avanzados para citar y formatear citas en múltiples lenguajes y estilos.

 * [siunitx](https://ctan.org/pkg/siunitx) — Proporciona símbolos utilizados en el sistema internacional de medida, como grados, minutos, segundos, ohmios, kilo, micro, julios y newtons, entre muchos otros.
