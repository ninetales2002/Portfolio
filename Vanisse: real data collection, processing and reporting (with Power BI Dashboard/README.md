El siguiente proyecto tiene como objetivo recolectar datos de ventas reales de un negocio minorista y preprocesarlos para crear un dashboard en PowerBI que reporte información sobre las ventas realizadas. 

El dataset contiene la siguiente información detallada sobre las ventas, incluyendo datos sobre los clientes, productos, métodos de pago y precios:

- n_cliente: número de identificación de cada visita al local que realiza una compra. Este número permite rastrear las compras realizadas por cada persona y analizar el comportamiento de compra.

- fecha_y_hora: fecha y hora de la compra. Registra el momento exacto en que se realizó la transacción. Esta información es útil para análisis temporales, como identificar patrones de compra en diferentes momentos del día, días de la semana o épocas del año.

- nombre_producto: descripción textual del producto adquirido. Facilita la identificación del producto y permite realizar análisis sobre la popularidad de distintos productos.

- metodo_pago: método de pago utilizado para la compra. Especifica cómo se realizó el pago, por ejemplo, efectivo, tarjeta de crédito, tarjeta de débito, QR, etc. Esta información es importante para entender las preferencias de pago de los clientes.

- codigo_barras: identificador único del producto que puede ser escaneado para agilizar el proceso de venta y registro.

- precio_contado: precio del producto si se paga al contado.

- precio_lista: precio del producto si se paga mediante débito, crédito o QR.

- total_compra_efectivo: es la suma total de los precios de los productos adquiridos en una transacción específica cuando el pago se realiza en efectivo.

- total_compra_lista: es la suma total de los precios de los productos de la compra si se paga mediante débito, crédito o QR.

- 3_pagos: costo del producto cuando el pago se fracciona en tres pagos.

- marca: nmbre del fabricante o la marca del producto. Ayuda en el análisis de la preferencia de marca y en la gestión de inventarios de productos de distintas marcas.

- categoria: clasificación del producto en una categoría específica, como alimentos, bebidas, electrónica, etc. Esta clasificación es útil para análisis de ventas por categoría y para la organización de productos en el punto de venta.

Los datos fueron recolectados mediante la plataforma Airtable, que permitió un cómodo registro de los datos gracias a sus funciones intuitivas y amigables. Airtable facilitó esta tarea mediante características como la vinculación de registros de otras tablas, generación automática de ID's de fila y de datos datetime, y sincronización en tiempo real.

Una imagen estática del dashboard resultante se muestra a continuación:

![Dashboard](dashboard.png)
