"""
Interactuá con dos IAs distintas para generar el sitio web pedido y resolvé las siguientes consignas:

Armá el prompt con el que interactuarás con ambas IAs (debe ser el mismo en ambos casos).

Generá las dos versiones del sitio pedido y subilo a un repositorio git en dos directorios distintos: uno por cada versión.

Analizá ambos sitios con validadores de HTML, CSS y accesibilidad.

Generá un informe con el formato indicado y subilo, en formato PDF renombrando el documento como “informe_<APELLIDO> (ejemplo “Informe_BANCHOFF”),  a la tarea  TEORIA - ACT 1

Tenemos que generar un sitio web estatico (sin scripts) para anunciar mascotas perdidas.
La informacion a mostrar esta en dos directorios: uno denominado "imagenes", con una imagen representativa de cada mascota y otro denominado "info", con un pdf con informacion sobre la misma. Para esto, hay que contemplar las siguientes condiciones:
    1. Se debe mostrar una barra de navegacion (dispuesta como mas les guste) con enlaces a:
        .Informacion de contacto (un formulario simple con los datos que les parezcan mas adecuados para esta seccion)
        .Informacion de quien mantiene el sitio
        .Listado con los datos de las mascotas perdidas (foto y descripcion) dividido en 2 categorias: perros y gatos
    2.Pueden indicar los colores y estilos que prefieran
    3.Respecto a la interaccion con el sitio, se debe poder elegir una categoria (ya sea desde una lista de opciones desplegable o radio buttons o la opcion que prefieran), y al seleccionar dicha categoria, mostrar los datos correspondientes en la zona central de la pagina. Siempre en forma estatica.
    4.Las imagenes con las fotos de las mascotas deben mostrarse todas con un mismo borde y un relleno al mismo de manera tal que la visualizacion sea armonica. Algo similar a: *imagen*
    5.El sitio debe ser responsive
    6.Solo se debe usar HTML y CSS
    7.Las reglas de estilo deben estar en un archivo separado denominado estilosIA.css
    8.Se debe trabajar con al menos 3 macotas por cada categoria a mostrar.
"""