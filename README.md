# automatizacion-asistencia
Automatización de registros de asistencia con n8n, Gemini y Google Sheets

## ¿Qué problema resuelve?
Cargar las planillas una por una a mano de los empleados de una empresa

## ¿Cómo funciona?
1. Le envio captura de las planillas a un BOT de telegram
2. Gemini procesa la imagen y extrae la información
3. n8n resuelve el flujo completo
4. Los datos se vuelcan automáticamente en Google Sheets

## Resultado
- 100% de carga manual eliminada
- Solamente reveisar por arriba por algun error de la IA
- Tiempo optimizado

## Stack
- n8n (automatización)
- Google Gemini API (procesamiento de imágenes)
- Google Sheets (almacenamiento)
- Telegram (interfaz de entrada)
