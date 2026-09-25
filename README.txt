INVENTARIO DE MONITORES V2 - DELL / SAMSUNG

Cambios principales
- Soporte de Data Matrix además de QR.
- También intenta leer Code 128 y Code 39.
- Campos específicos de Dell:
  * Modelo
  * Service Tag
  * S/N
  * Express Service Code
  * MAC Address
  * Fecha de fabricación
- Reglas genéricas para etiquetas Samsung:
  * Model / Model Code / Type No
  * S/N / Serial
- OCR con preprocesamiento de imagen para etiquetas oscuras con texto claro.
- Detección de posibles registros duplicados.
- Conserva Usuario, Área y Ubicación después de guardar para acelerar inventario por piso/zona.
- Exportación CSV para Excel.

USO RECOMENDADO
1. Abrir la aplicación desde HTTPS en el celular.
2. Iniciar cámara y escanear uno o ambos códigos 2D de la etiqueta.
3. Tomar una foto completa de la etiqueta y ejecutar OCR.
4. Revisar/corregir los datos.
5. Completar Usuario, Área y Ubicación.
6. Guardar y pasar al siguiente monitor.
7. Exportar CSV al terminar cada bloque de trabajo.

IMPORTANTE
- La cámara del navegador normalmente requiere HTTPS o localhost.
- Las librerías de lectura de códigos y OCR se cargan desde Internet.
- Los datos se guardan localmente en el navegador hasta su exportación.
