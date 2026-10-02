# Playground WooCommerce: tienda demo para clase

Entorno de práctica para aprender a montar un ecommerce con WooCommerce. Corre en tu navegador. No necesitas hosting, instalación ni cuenta.

## Iniciar

**[Abrir tienda demo](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/senkik85/playground-woocommerce/main/blueprint-tienda-demo.json)**

Espera 20 a 40 segundos mientras carga. Entrarás directo al panel de WooCommerce, ya con sesión iniciada.

## Qué incluye

- WooCommerce instalado y activo
- País México, moneda MXN, zona horaria CDMX
- 3 categorías: Ropa, Accesorios, Digitales
- 5 productos: simples, uno en oferta, uno variable por talla y uno digital
- Cupón de ejemplo: `BIENVENIDO10` (10%)

Envíos, impuestos y pagos vienen sin configurar. Son parte de los ejercicios.

## Ejercicios

Ver [ejercicios-woocommerce.md](ejercicios-woocommerce.md). 8 módulos, cada uno con su entregable.

## Reglas del entorno

- **Los datos son temporales.** Si cierras o recargas la pestaña, pierdes todo.
- Para guardar tu avance: menú de Playground > Descargar como .zip.
- Para repetir desde cero: vuelve a abrir el link de arriba.
- La tienda no tiene URL pública. No se puede compartir.
- Pasarelas reales (Stripe, PayPal, Mercado Pago) y correos no funcionan aquí.
- Usa Chrome, Edge o Firefox actualizados. Evita el modo incógnito si quieres guardar el sitio en el navegador.

## Problemas comunes

| Problema | Solución |
|---|---|
| Pantalla en blanco o carga infinita | Recarga la página. Si persiste, prueba otro navegador. |
| El panel aparece en inglés | Ajustes > General > Idioma del sitio > Español de México. |
| No aparecen los productos | Recarga el link. El Blueprint corre solo al iniciar. |
| Perdí mi trabajo | Es temporal. Descarga el .zip antes de cerrar. |

## Estructura del repo

```
├── README.md
├── blueprint-tienda-demo.json
└── ejercicios-woocommerce.md
```

## Para el instructor

- No cambies el nombre del archivo ni la rama una vez repartido el link.
- GitHub cachea el raw unos 5 minutos tras editar.
- Para congelar versión, sustituye `main` en la URL por un hash de commit.
- Para modificar el Blueprint, usa [Blueprint Builder](https://playground.wordpress.net/builder).
