# FichApp PWA Wrapper - Guía de Despliegue

Esta carpeta contiene la solución **PWA Wrapper** diseñada para transformar Google Apps Script Web App en una aplicación instalable sin modificar ni una sola línea de código backend actual.

## 📁 Contenido
- `index.html`:  Carga tu Web App dentro de un marco seguro.
- `manifest.json`: Archivo de configuración que hace la app instalable (nombre, colores, iconos).
- `sw.js`: Service Worker que permite guardar esta cáscara en el móvil para que abra rápido.
- `offline.html`: Pantalla de error amigable cuando no hay internet.

## 🚀 Pasos para Desplegar (Hosting Gratuito)
### 1. Configurar la URL de tu Web App
### 2. Preparar Iconos

   - `icon-192x192.png` (192x192 px)
   - `icon-512x512.png` (512x512 px)

### 3. Subir a un Hosting (Recomendado: GitHub Pages)
## 📲 Cómo Instalar
1. Abre la URL GitHub/url dominio en el navegador de tu móvil (Chrome en Android, Safari en iOS).
2. **Android**: Verás un aviso "Añadir FichApp a pantalla de inicio" o ve al menú -> "Instalar aplicación".
3. **iOS**: Pulsa el botón "Compartir" (cuadrado con flecha) -> "Añadir a pantalla de inicio".

¡Listo! Tu aplicación Apps Script ahora se comporta como una app nativa.
