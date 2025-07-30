# Invitación XV - Briana Alejandra

Invitación digital elegante para XV años con diseño responsivo y animaciones.

## 🚀 Despliegue en Vercel

### Opción 1: Despliegue Automático (Recomendado)

1. **Sube a GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Invitación XV"
   git remote add origin https://github.com/tu-usuario/invitacion-xv.git
   git push -u origin main
   ```

2. **Conecta con Vercel:**
   - Ve a [vercel.com](https://vercel.com)
   - Conecta tu cuenta de GitHub
   - Importa el repositorio
   - Vercel detectará automáticamente la configuración

### Opción 2: Despliegue Manual

1. **Instala Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Despliega:**
   ```bash
   vercel
   ```

## 📁 Estructura del Proyecto

```
Invitacion_XV/
├── index.html          # Página del sobre
├── invitacion.html     # Invitación completa
├── styles.css          # Estilos y animaciones
├── vercel.json         # Configuración de Vercel
├── README.md           # Este archivo
└── imagenes/           # Carpeta de imágenes
    ├── sobre.png
    ├── sello.png
    ├── img1.jpeg
    └── ...
```

## 🎨 Características

- ✅ Diseño responsivo
- ✅ Animaciones suaves
- ✅ Cuenta regresiva
- ✅ Formulario de registro
- ✅ Galería de fotos
- ✅ Optimizado para móvil

## 🔧 Personalización

### Cambiar fecha del evento:
Edita en `invitacion.html` línea 108:
```javascript
const fechaEvento = new Date('2025-08-30T14:00:00');
```

### Cambiar enlace del formulario:
Edita en `invitacion.html` línea 67:
```html
<a href="TU_LINK_AQUI" class="btn-registro">
```

## 📱 URLs

- **Página principal:** `tu-dominio.vercel.app`
- **Invitación directa:** `tu-dominio.vercel.app/invitacion`

## 🎯 Optimizaciones Incluidas

- ✅ Compresión de imágenes automática
- ✅ Cache optimizado
- ✅ Rutas configuradas
- ✅ Headers de rendimiento

¡Listo para desplegar! 🚀