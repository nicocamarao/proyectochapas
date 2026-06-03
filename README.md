# OCR de Chapa UY

App HTML5 simple que:

- abre la cámara con `getUserMedia`
- corre OCR con OCR.space desde el navegador
- prueba varios recortes y preprocesados para detectar matrículas uruguayas
- consulta `https://chapauy.leak.com.ar/offenses?vehicle=...`

## Uso local

Abrilo desde un servidor estático HTTPS o `localhost`, porque la cámara no funciona desde `file://`.

## Deploy

1. Crear un repo nuevo en GitHub.
2. Subir `index.html` y `README.md`.
3. Activar GitHub Pages desde la rama `main`.

## Nota de seguridad

El token que pegaste quedó expuesto en el chat. Lo correcto es revocarlo y generar uno nuevo con permisos mínimos antes de usarlo otra vez.
