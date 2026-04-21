n# 📋 MisVencimientos — PWA

App de gestión de suministros, seguros y pagos recurrentes.
Funciona sin conexión y se instala en iPhone como app nativa.

---

## 🚀 Cómo publicarla (gratis en Netlify)

### Opción A — Arrastra y suelta (más fácil)

1. Ve a **https://netlify.com** y crea una cuenta gratuita
2. En el panel principal, busca la zona que dice **"drag and drop your site folder here"**
3. Arrastra la carpeta `misvencimientos` completa ahí
4. En segundos tendrás una URL tipo: `https://nombre-aleatorio.netlify.app`
5. ¡Listo! Puedes cambiar el nombre en Settings → Domain management

### Opción B — GitHub + Netlify (recomendada para actualizaciones)

1. Sube la carpeta a un repositorio en **github.com**
2. En Netlify: New site → Import from Git → selecciona el repo
3. Cada vez que actualices el código en GitHub, la app se actualiza sola

---

## 📱 Instalar en iPhone

1. Abre la URL de tu app en **Safari** (importante: debe ser Safari, no Chrome)
2. Pulsa el botón **Compartir** (cuadrado con flecha hacia arriba)
3. Desplázate y pulsa **"Añadir a pantalla de inicio"**
4. Dale el nombre que quieras → **Añadir**
5. Ya aparece el icono en tu pantalla de inicio como una app normal

---

## 📁 Archivos del proyecto

```
misvencimientos/
├── index.html      ← La app completa
├── manifest.json   ← Configuración PWA (nombre, colores, icono)
├── sw.js           ← Service Worker (funciona sin internet)
└── README.md       ← Este archivo
```

> **Nota:** Los datos se guardan en el dispositivo (localStorage).
> No se envía nada a ningún servidor.

---

## ✨ Funciones

- ✅ Avisos visuales: vencido / urgente / próximo / al día
- ✅ Categorías: seguros, hogar, vehículo, suministros, finanzas
- ✅ Marcar como pagado → avanza la fecha automáticamente
- ✅ Dashboard con gasto mensual estimado
- ✅ Funciona sin conexión a internet
- ✅ Datos guardados en tu móvil (privados, no en la nube)
