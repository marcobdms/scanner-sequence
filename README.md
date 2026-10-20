# Secuencia de escáneres

Herramienta de un solo archivo (`index.html`) para configurar escáneres inalámbricos con su base.
Muestra los códigos de barras de uno en uno, en grande, para escanearlos rápido desde la pantalla.

- Sin instalación ni servidor: doble clic en `index.html` (Chrome o Edge).
- No usa red, así que la VPN de Cisco no influye.
- Los datos se guardan en el navegador (`localStorage`).

## Llevar los recortes a otro equipo

1. Pulsa **Exportar**: descarga `datos.js` con todos los recortes y el orden.
2. Ponlo en la misma carpeta que `index.html` y copia la carpeta al otro equipo.
3. Al abrir `index.html` se carga solo. Si el navegador tiene datos más nuevos, usa esos.

Vuelve a exportar cada vez que cambies algo.

## Uso

1. Recorta cada código del manual (Win+Shift+S), haz clic en su tarjeta y pega con Ctrl+V. Deja margen blanco alrededor.
2. Ordena: ↑ ↓, arrastrar desde ⠿, o ⇄ para intercambiar dos tarjetas. Edita nombre y comando escribiendo encima.
3. El punto de color cambia el tipo de paso: normal o alarma. Se reproduce todo en el orden del editor; el toggle **Estación con Windows** quita solo los pasos de alarma.
4. **Reproducir**: Espacio / → / clic avanza, ← vuelve, + − cambia el tamaño (en saltos enteros, para que las barras no se deformen), R repite, Esc sale.
   Enter no avanza a propósito, por si un escáner con auto-enter está vinculado a ese portátil.

## Confidencialidad

El manual de origen está marcado como confidencial. Este repositorio **no incluye imágenes de códigos**:
solo la plantilla de pasos. Mantén las capturas fuera del repo (el `.gitignore` bloquea `datos.js` e imágenes).
