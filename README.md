# Sistema-Cat-logo-Tienda
OBJETIVO
El programa es un sistema de consola diseñado para gestionar el catálogo de productos 
de una microempresa mediante el uso de diccionarios anidados en Python, asociando un 
código alfanumérico único a la descripción detallada de cada artículo (nombre, precio
unitario y cantidad en bodega)
REQUISITOS PARA EJECUTAR
Contar con un entorno o intérprete de Python instalado en el computador para ejecutar
el archivo de código fuente directamente desde la terminal o consola de comandos
FUNCIONES IMPLEMENTADAS
1. buscar_producto(): Permite realizar una búsqueda segura de una artículo utilizando
   el método .get() y emite una advertencia si el código no se encuentra registrado
2. ingresar_existencias(): Incrementa de forma controlada el valor del stock de un
   producto existente a partir de su código
4. registrar_producto(): Facilita el ingreso de un nuevo producto al catálogo,
   implementando validaciones para prevenir la sobreescritura de datos preexistentes
   sin previa confirmación
5. calcular_valor_inventario(): Recorre el catálogo completo para calcular el valor
   monetario total del inventario disponible multiplicando el precio por el stock de
   cada producto
INSTRUCCIONES DE USO
Al iniciar el script, se mostrará un menú interactivo en la consola con opciones
numeradas del 1 al 5. El usuario debe digitar el número de la acción que desea
realizar (como buscar, actualizar existencias, registrar un producto o calcular el
inventario) y seguir las indicaciones en pantalla ingresando los datos solicitados
