# FT Style Barbería · Tarjeta de sellos digital

Tarjeta de fidelización en un solo archivo HTML (`index.html`).

- 8 sellos. Al 4.º, 30% de descuento en ese mismo corte. Al completar los 8, el próximo corte es gratis.
- El sello se valida con el QR del mostrador (`index.html#mostrador`, PIN de prueba `1234`).
- Datos del local y del desarrollador editables en el bloque `CFG` y `DEV` del script.

> Versión de presentación: la validación corre en el navegador. Para producción se conecta a Supabase (firma del QR y límite de 24 h en el servidor).

Potenciado y desarrollado por Rave Holding | Soluciones de Digitalización Comercial
