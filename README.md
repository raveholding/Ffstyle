# FT Style Barbería · Tarjeta de sellos digital

Tarjeta de fidelización en un solo archivo HTML (`index.html`).

- 8 sellos. Al 4.º, 30% de descuento en ese mismo corte. Al completar los 8, el próximo corte es gratis.
- Menú del dueño (candado abajo a la izquierda, PIN de prueba `1234`): genera el QR de sello para cada cliente y deja el registro en el WhatsApp del local, listo para reenviar al cliente.
- El cliente completa su tarjeta con nombre, WhatsApp y cumpleaños (opcional), con consentimiento (Ley 25.326); puede editar o borrar sus datos.
- El dueño puede editar o borrar cada registro de sellos, o todo el registro.
- El cliente escanea el QR, suma su sello y puede enviar el comprobante al WhatsApp del local.
- Datos del local y del desarrollador editables en el bloque `CFG` y `DEV` del script.

> Versión de presentación: la validación corre en el navegador. Para producción se conecta a Supabase (firma del QR y límite de 24 h en el servidor).

Potenciado y desarrollado por Rave Holding | Soluciones de Digitalización Comercial
