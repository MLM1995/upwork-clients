# 58. LinkedIn Profile Data Scraper Needed

- Cliente: Noura Almazrou (Arabia Saudí; encargo pagado de su bolsillo para estudiar empresas inmobiliarias)
- Upwork workroom: https://www.upwork.com/nx/wm/workroom/41333798/overview
- Room de mensajes: https://www.upwork.com/ab/messages/rooms/room_520e534ab56d5a85cf4a952dfe3557bb
- Fechas: 9 ago 2025 a 10 ago 2025 (mensajes hasta el 11 ago)
- Estado: Ended (cerrado por la clienta sin completar)
- Importe: 30,00 USD precio fijo; total cobrado: 0,00 USD (devolución aprobada el 10 ago 2025)
- Hitos: M1 Get the setup ready and scrape 50% of the data, 15,00 USD, financiado y devuelto (vencimiento 9 ago); M2 Get the setup ready and scrape 100% of the data, 15,00 USD, no iniciado (vencimiento 10 ago)
- Valoración: sin feedback por ninguna de las dos partes. En julio de 2026 Upwork marca a la clienta como restringida
- Web del cliente: no aparece
- Plataforma: no aplica
- Sector (nicho): Microtareas, research y testing
- Sector alternativo: Inmobiliario e inversión

## Resumen del proyecto
Noura quería en 24 horas un Google Sheet con todos los empleados de LinkedIn de cuatro empresas inmobiliarias de Arabia Saudí y Emiratos (Bayut KSA, Mada Properties, Rakez y Huspy, unos 1.650 perfiles), con más de 10 datos por persona: puesto, tipo de contrato, ubicación, experiencia, universidad, estudios y contacto. Marcos entregó una primera extracción con datos básicos (nombre, URL, puesto, ubicación). Luego se le bloqueó la cuenta de Sales Navigator, y con Apollo no salían todos los perfiles ni todos los datos (por ejemplo, 517 de Huspy en vez de 750). Marcos propuso cancelar y la clienta cerró el contrato con devolución. Al día siguiente hablaron de un posible encargo de scraping de TikTok (vídeos inmobiliarios en árabe con métricas de engagement, tipo de inmueble y zona); Marcos hizo una prueba con una cuenta, pero no llegó a contratarse.

## Decisiones y acuerdos clave
- 30 USD por unas 1.650 personas (unos 0,018 USD por lead), en dos hitos del 50 %, con plazo máximo de 24 horas
- Una hoja por empresa y una fila por persona; celdas vacías si falta un dato, sin inventar
- Se cancela al no poder sacar los datos completos sin Sales Navigator

## Entregables y archivos intercambiados
| Fecha | Quién | Archivo | Tamaño | Qué es |
|---|---|---|---|---|
| 9 ago 2025 | Marcos | Local Contractors - Sioux Falls.csv | 69 kB | Ejemplo de datos de otro trabajo de scraping |
| 9 ago 2025 | Marcos | Huspy.jpg | no consta | Número de miembros de Huspy |
| 9 ago 2025 | Noura | image.png | 119,62 kB | Formato esperado de la hoja |
| 9 ago 2025 | Marcos | Dos Google Sheets (datos en bruto y modelo limpio) | no aplica | Primera extracción de perfiles |
| 10 ago 2025 | Marcos | apollo-accounts-export - apollo-accounts-export.csv.csv | 17 kB | Exportación de Apollo con cobertura parcial |
| 10 ago 2025 | Marcos | Huspy.jpg, KSA.png, Rakez.jpeg y Mada Properties.jpg | no consta | Contactos disponibles por empresa |
| 11 ago 2025 | Noura | image.png (3) | no consta | Ejemplos del análisis de TikTok deseado |
| 11 ago 2025 | Marcos | Dos Google Sheets de TikTok | no aplica | Prueba de extracción de vídeos de una cuenta |
| 11 ago 2025 | Marcos | IMG_6193.jpeg | 6,47 MB | Precio de la suscripción a DICloak |

## Pendientes o notas para el futuro
- Lección: no aceptar scraping masivo de LinkedIn a precio tan bajo sin tener antes la herramienta asegurada
