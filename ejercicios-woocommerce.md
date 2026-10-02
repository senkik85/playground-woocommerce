# Ejercicios: montar un ecommerce con WooCommerce

Entorno: WordPress Playground con el Blueprint `blueprint-tienda-demo.json`.
Precargado: WooCommerce, país México, moneda MXN, 5 productos, 3 categorías, cupón `BIENVENIDO10`.
Aviso a alumnos: al cerrar o recargar se pierde todo. Exporten el ZIP al terminar.

## Módulo 1. Reconocer el panel
- Abrir WooCommerce > Inicio y revisar la lista de tareas.
- Ubicar: Productos, Pedidos, Clientes, Marketing, Ajustes.
- Visitar la tienda como cliente (menú superior > Visitar sitio).
- Entregable: captura de la tienda y lista de 3 cosas que cambiarían.

## Módulo 2. Productos
- Editar "Taza de cerámica": añadir descripción corta, etiqueta y imagen (subir cualquier imagen).
- Crear un producto simple nuevo con precio y precio rebajado programado.
- Revisar la variable "Playera básica": cambiar precio de la talla L, agregar talla XL.
- Crear un producto agrupado o externo/afiliado.
- Entregable: 3 productos propios con categoría, imagen y stock.

## Módulo 3. Envíos
- WooCommerce > Ajustes > Envío > crear zona "México".
- Tarifa plana de $99.
- Envío gratis arriba de $999 (método "Envío gratuito" con monto mínimo).
- Probar en el carrito que cambie el costo al pasar el umbral.
- Entregable: captura del carrito con envío gratis activado.

## Módulo 4. Impuestos
- Ajustes > General > activar impuestos.
- Pestaña Impuestos: tasa estándar IVA 16% para MX.
- Decidir precios con o sin IVA incluido y ver el efecto en tienda.
- Entregable: producto de $100 mostrado con IVA y desglose en el carrito.

## Módulo 5. Pagos
- Ajustes > Pagos: activar transferencia bancaria y pago contra entrega.
- Personalizar instrucciones de pago.
- Nota: pasarelas reales (Stripe, Mercado Pago) se enseñan en hosting real.
- Entregable: captura del checkout con 2 métodos de pago.

## Módulo 6. Pedido de prueba completo
- Como cliente: agregar productos, aplicar `BIENVENIDO10`, finalizar compra.
- Como admin: abrir el pedido, cambiar estado (procesando > completado), agregar nota, hacer reembolso parcial.
- Entregable: pedido completado con cupón y reembolso.

## Módulo 7. Cupones y marketing
- Crear cupón de envío gratis con fecha de vencimiento y límite de uso.
- Crear cupón de $50 mínimo de compra $500.
- Revisar WooCommerce > Analítica con los pedidos de prueba.

## Módulo 8. Diseño
- Apariencia > Editor: personalizar página de inicio, menú y página de producto.
- Probar un tema nuevo (Temas > Añadir nuevo).
- Entregable: portada con banner, productos destacados y categorías.

## Cierre
- Menú de Playground > Descargar como .zip.
- Tarea: repetir la configuración en staging o hosting real.
