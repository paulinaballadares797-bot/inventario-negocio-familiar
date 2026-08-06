# Requisitos del proyecto

## Objetivo

Contar con un sistema digital simple que permita registrar y consultar
el inventario de perfumes del negocio familiar, evitando la pérdida de
información que actualmente ocurre con el registro en papel.

## Alcance

El proyecto abarca únicamente la propuesta conceptual de una solución de
inventario digital: definición del problema, funcionalidades, requisitos
y planificación. No incluye desarrollo de software ni código fuente.

## Usuarios principales

* Miembros de la familia que atienden el negocio (registro y consulta
de productos).
* Persona encargada de compras y reposición de stock.

## Requisitos funcionales (priorizados)

### Alta prioridad

1. Registrar perfumes con nombre, marca, presentación (ml) y precio.
2. Registrar entradas de mercadería (compras/reposición).
3. Registrar salidas de mercadería (ventas).
4. Mostrar el stock disponible de cada perfume en tiempo real.
5. Validar que no se permitan registrar salidas cuando el stock disponible sea insuficiente.

### Media prioridad

5. Emitir alerta cuando un perfume tenga stock bajo.
6. Mostrar historial de movimientos (entradas/salidas) por fecha.
7. Permitir búsqueda de productos por nombre o marca.
8. Permitir editar o actualizar la información de un perfume registrado, como precio o presentación.

### Baja prioridad

8. Generar un reporte simple de los perfumes más vendidos.
9. Registrar qué persona hizo cada movimiento.
10. Permitir filtrar el historial de movimientos por rango de fechas.

## Requisitos no funcionales

* La información debe quedar respaldada (evitar pérdida de datos).
* El sistema debe ser fácil de usar para personas sin conocimientos
técnicos avanzados.
* Debe poder consultarse desde un celular o computadora.
* La información del inventario debe actualizarse de forma inmediata después de registrar una compra o una venta. 
* El sistema debe proteger el acceso mediante usuario y contraseña para evitar modificaciones no autorizadas.

