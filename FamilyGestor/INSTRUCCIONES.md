# 📱 Instalación de Travel Calculator en iPhone 11

## ¿Cómo instalar la aplicación en tu iPhone?

### Opción 1: Instalación como App Web (Recomendado)

1. **Abre Safari** en tu iPhone 11
2. Ve al sitio donde está alojada la app (o abre el archivo `index.html`)
3. Presiona el icono de **Compartir** (flecha hacia arriba)
4. Desplázate y selecciona **"Agregar a pantalla de inicio"**
5. Pon un nombre a la app (ej: "Travel Calculator")
6. Presiona **"Agregar"**

¡Listo! Ahora verás la app como un icono en tu pantalla de inicio.

### Opción 2: Si tienes un servidor web

Para una experiencia mejor, puedes subir los archivos a un servidor:

1. **Archivos necesarios:**
   - `index.html` - Archivo principal
   - `manifest.json` - Configuración de la app
   - `sw.js` - Service Worker para offline

2. **Sube los archivos a tu servidor web** (Netlify, Vercel, GitHub Pages, etc.)

3. **En Safari de iPhone:**
   - Abre la URL de tu sitio
   - Presiona el icono Compartir
   - Selecciona "Agregar a pantalla de inicio"

### Opción 3: Archivo HTML local

Si quieres usar el archivo HTML directamente:

1. **Descarga** el archivo `index.html` a tu iPhone
2. **Abre en Safari**
3. Presiona Compartir → "Agregar a pantalla de inicio"

---

## 📋 Características de la App

✅ **Completamente offline** - Funciona sin conexión a internet
✅ **Sincronización automática** - Guarda todos tus datos
✅ **Interfaz optimizada** - Perfecta para iPhone
✅ **Gestor de viajes** - Registra, busca y filtra viajes
✅ **Tarifas personalizables** - Actualiza los precios cuando quieras

---

## 🔧 Qué hace cada archivo

- **index.html**: Contiene toda la aplicación
- **manifest.json**: Define cómo se ve la app en pantalla
- **sw.js**: Permite usar la app sin internet

---

## 💾 Almacenamiento de datos

Todos tus viajes y tarifas se guardan **localmente en tu iPhone** usando localStorage.
Los datos NO se sincronizan entre dispositivos, pero se guardan automáticamente cada vez que registras un viaje.

---

## 🚀 Solución de problemas

### La app no aparece como opción
- Asegúrate de estar usando **Safari** (no Chrome)
- Recarga la página y espera 2 segundos antes de compartir

### No se guarda los datos
- Verifica que no hayas bloqueado localStorage en Safari
- Ve a Configuración → Safari → Privacidad → Borrar datos al cerrar (desactiva esto)

### La app se cierra al abrirla
- Intenta abrir en Safari nuevamente
- Limpia el caché: Configuración → Safari → Borrar historial y datos

---

## 📞 Soporte

Si tienes problemas:
1. Asegúrate de que Safari está actualizado
2. Intenta agregar la app nuevamente a la pantalla de inicio
3. Reinicia el iPhone

---

## 🎨 Personalización

Si quieres cambiar:
- **Colores**: Modifica los valores en la sección `<style>` del HTML
- **Tarifas iniciales**: Busca `tarifa1: 7500` en el código
- **Nombre de la app**: Cambia el valor en `manifest.json` bajo `"short_name"`

---

¡Disfruta usando Travel Calculator en tu iPhone! 🚕
