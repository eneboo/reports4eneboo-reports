Reports fusiodarts v1.0
======================

Estos reports han sido creados con varios subreports, uno por cada seccion del documento. De esta forma podemos reutilizar los diferentes subreports en todos los documentos sin tener que volver a crearlos individualmente por report.

Para poder realizar esta tarea ha sido necesario crear varios parametros que mandan la información de la tabla, titulo, etc...
Las variables creadas han sido:

 * TITLE_REPORT
 * TEXT_REPORT
 * TABLE_REPORT

 Estas variables se definen en los reports master y se encargan de pasarle la informacion necesaria para hacer la consulta y rellenar los diferentes campos a los subreports.
 
Archivo de estilo
------------------
Dentro del directorio de los reports encontrareis un archivo llamado style.jrtx, en el se define el color de las cabeceras y el color de las lineas de los recuadros.
Todos los reports y subreports usan este archivo de estilo, que no se puede mover de su ubicación original.

------------------

Espero que os sea de gran ayuda, saludos.


*Podeis visitar nuestra web en [www.fusiodarts.com](http://www.fusiodarts.com)* o poneros en contacto con nosotros a través de contacto@fusiodarts.com
