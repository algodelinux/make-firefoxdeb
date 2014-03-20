make-firefoxdeb
===============

make-firefoxdeb genera un paquete Debian de Firefox para la arquitectura que le indiquemos

Este script:
   * Descarga el fichero .tar.bz2 de la última versión de Firefox disponible en http://ftp.mozilla.org
   * Crea el paquete Debian para la arquitectura que le indiquemos como parámetro

Modo de uso:
   makefirefoxdeb i386 (para crear el paquete i386)
   makefirefoxdeb amd64 (para crear el paquete amd64)

Observaciones: 
   * Ejecutar el script en un sistema de 32 bits para generar el paquete de 32 bits
   * Ejecutar el script en un sistema de 64 bits para generar el paquete de 64 bits

