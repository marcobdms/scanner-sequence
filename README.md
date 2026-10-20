# Secuencia de escáneres

Herramienta de un solo archivo (`index.html`) para configurar escáneres inalámbricos con su base.
Muestra los códigos de barras de uno en uno, en grande, para escanearlos rápido desde la pantalla.

- Sin instalación ni servidor: doble clic en `index.html` (Chrome o Edge).
- No usa red, así que la VPN de Cisco no influye.
- Los datos se guardan en el navegador (`localStorage`). Usa **Exportar** para llevar una copia a otro equipo.

## Uso

1. Recorta cada código del manual (Win+Shift+S), haz clic en su tarjeta y pega con Ctrl+V. Deja margen blanco alrededor.
2. Ordena: ↑ ↓, arrastrar desde ⠿, o ⇄ para intercambiar dos tarjetas. Edita nombre y comando escribiendo encima.
3. El punto de color cambia el tipo de paso: normal, alarma (se salta en estaciones Windows) o fuera del flujo.
4. **Reproducir**: Espacio / → / clic avanza, ← vuelve, + − cambia el tamaño, R repite, Esc sale.
   Enter no avanza a propósito, por si un escáner con auto-enter está vinculado a ese portátil.

## Confidencialidad

El manual de origen está marcado como confidencial. Este repositorio **no incluye imágenes de códigos**:
solo la plantilla de pasos. Mantén las capturas fuera del repo (el `.gitignore` bloquea los `.json` exportados).
