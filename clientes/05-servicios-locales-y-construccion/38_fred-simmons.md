# 38. WordPress Site Speed Optimization Expert Needed

- Cliente: Fred Simmons (Blanton & Sons, empresa de climatización y fontanería, Charleston, Carolina del Sur, Estados Unidos)
- Upwork workroom: https://www.upwork.com/nx/wm/workroom/42673515/overview
- Room de mensajes: https://www.upwork.com/ab/messages/rooms/room_51972efd5079dbf2cbcd0a9e3c0da963
- Fechas: 16 ene 2026 a 9 jun 2026 (el trabajo se paró el 22 ene; Marcos cerró el contrato en junio)
- Estado: Ended (cerrado antes de tiempo)
- Importe: 400,00 USD precio fijo; total cobrado: 100,00 USD
- Hitos: M1 Audit, 100,00 USD, pagado, 16 ene 2026; M2 Optimizae, 200,00 USD, no iniciado (vencimiento 18 ene); M3 Finish, 100,00 USD, no iniciado (vencimiento 19 ene)
- Valoración: sin feedback del cliente; Marcos le dio 5.0/5
- Web del cliente: https://blantonandsons.com
- Plataforma: WordPress
- Sector (nicho): Servicios locales y construcción
- Sector alternativo: ninguno

## Resumen del proyecto
Fred quería acelerar su WordPress (tema Frost child en Cloudways con Breeze y Cloudflare), que cargaba herramientas de reserva de terceros y tenía campañas de pago activas. Marcos envió una propuesta de precio fijo y empezó por la auditoría en staging vía SFTP. La auditoría concluyó que el problema estaba en móvil y lo causaban scripts de terceros que se cargaban pronto (sobre todo el scheduler de ServiceTitan, los widgets de chat y, según el cliente, GTM), y que hosting y CDN no eran el cuello de botella. Recomendó retrasar o condicionar la carga de ServiceTitan en móvil y priorizar el recurso LCP. Fred aprobó el hito de auditoría, pero Marcos tuvo problemas de acceso repetidos porque el SFTP exigía una IP fija en lista blanca, y el 22 de enero Fred decidió no seguir.

## Decisiones y acuerdos clave
- Precio fijo de 400 USD en tres hitos (auditoría 100, optimización 200, cierre 100)
- Sin acceso completo al servidor; se trabaja por SFTP con IP en lista blanca y primero en staging
- Enfoque aprobado: carga retrasada o condicional de ServiceTitan en móvil probada en staging
- El cliente cerró la colaboración por los problemas de acceso al no tener Marcos una IP fija
- El cliente compartió credenciales en el chat

## Entregables y archivos intercambiados
| Fecha | Quién | Archivo | Tamaño | Qué es |
|---|---|---|---|---|
| 16 ene 2026 | Marcos | WordPress Performance Optimization - Blanton & Sons .pdf | 66 kB | Propuesta con alcance, plazos y precio |
| 16 ene 2026 | Fred | Enlace de 1Password | no aplica | Acceso compartido a WordPress |
| 16 ene 2026 | Fred | Screenshot 2026-01-16 at 11.44.49 AM.png | no consta | Configuración SFTP de Cloudways |
| 16 ene 2026 | Marcos | SFTP.jpg | 359,52 kB | Confirmación de conexión SFTP a staging |
| 17 ene 2026 | Marcos | Performance Audit — Blanton & Sons.pdf | 210,82 kB | Auditoría de rendimiento con conclusiones |

## Pendientes o notas para el futuro
- Lección: para clientes con lista blanca de IP, conviene tener una IP fija o una VPN con IP dedicada
- Fred quedó en seguir en contacto para otros proyectos
- La auditoría ya identifica el plan de optimización por si el cliente vuelve
