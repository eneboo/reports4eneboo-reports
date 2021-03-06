Reports fusiodarts - reportUnico
================================
El reportUnico se puede utilizar en todos los documentos de facturacion de clientes (presupuestos, pedidos, albaranes y facturas). Solo debemos cambiar el titulo del documento para que cuando tengamos varios reports el selector salga con el nombre correcto.

Los reports que se encuentran en las carpetas *reports* son una copia del reportUnico.jrxml, todos con el mismo nombre.

Estos reports han sido creados con varios subreports, uno por cada sección del documento. De esta forma podemos reutilizar los diferentes subreports en todos los documentos y realizar cambios de una manera mas rápida.

Para que el report funcione necesitamos la extensión extF015-reportUnico que insertará el código para pasar los parametros necesarios al report.

Los parametros creados han sido:

 * PARAM_titulo (Nos inserta el titulo del documento -> Factura, Albaŕán, Pedido o Presupuesto)
 * PARAM_tabla (El nombre de las tablas -> facturascli, albaranescli, pedidoscli o presupuestoscli)
 * PARAM_subtabla (Necesario en algunos campos de la consulta -> factura, albaran, pedido, presupuesto)
 * PARAM_orderdef (Expresión por defecto en ORDERBY -> facturascli.codigo, albaranescli.codigo, pedidoscli.codigo o presupuestos.codigo)
 * PARAM_tablareldoc (Tabla del documento relacionado -> albaranescli o pedidoscli)
 * PARAM_reldoc (Necesario para documento relacionado -> albaran o pedido)


Logo
-----------------
Si se guarda un archivo logo.jpg de 555x92 se mostrará en toda la cabecera escondiendo los datos de la empresa.


Archivo de estilo
------------------
Dentro del directorio de los reports se encuentra un archivo llamado style.jrtx, en el se define el color de las cabeceras y el color de las lineas de los recuadros.
Todos los reports y subreports usan este archivo de estilo, que no se puede mover de su ubicación original.

------------------

Espero que sea de gran ayuda, saludos.


*Podeis visitar nuestra web en [www.fusiodarts.com](http://www.fusiodarts.com)* o poneros en contacto con nosotros a través de contacto@fusiodarts.com


DETALLES DE LAS OPCIONES
------------------------
- Cuenta bancaria y cuenta de cargo: 
	Si la factura tiene una forma de pago con la opción domiciliado se muestra la cuenta bancaria del cliente configurada coo domiciliada. Si la forma de pago no es domiciliada y tiene asociada una cuenta bancaria de la empresa se mostrará esta.