# 🍹 CLAP BAR - Escáner QR

Una aplicación web estática con escáner de códigos QR, diseñada para ser desplegada en GitHub Pages.

## ✨ Características

- 📱 **Escáner QR en tiempo real** usando la cámara del dispositivo
- 🎨 **Diseño moderno y responsivo** con gradientes y efectos visuales
- 🔒 **Privacidad total** - no se almacenan datos
- 📋 **Funciones útiles**: copiar texto y abrir enlaces automáticamente
- 🌐 **Compatible** con todos los dispositivos móviles y de escritorio
- ⚡ **Rápido y ligero** - optimizado para GitHub Pages

## 🚀 Cómo subir a GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a [GitHub](https://github.com) y crea un nuevo repositorio
2. Nombra el repositorio (ej: `clap-bar-qr-scanner`)
3. Marca como público
4. No inicialices con README (ya tienes este archivo)

### Paso 2: Subir los archivos
```bash
# Inicializar repositorio Git
git init

# Agregar archivos
git add .

# Hacer commit inicial
git commit -m "Initial commit: CLAP BAR QR Scanner"

# Conectar con tu repositorio de GitHub (reemplaza USERNAME y REPO)
git remote add origin https://github.com/USERNAME/REPO.git

# Subir a GitHub
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. Busca la sección **Pages** en el menú lateral
4. En **Source**, selecciona **Deploy from a branch**
5. Selecciona la rama **main** y la carpeta **/ (root)**
6. Haz clic en **Save**

### Paso 4: Acceder a tu sitio
Tu sitio estará disponible en: `https://USERNAME.github.io/REPO/`

## 📱 Uso de la aplicación

1. **Página principal** (`index.html`): Página de bienvenida con información sobre la app
2. **Escáner QR** (`qr.html`): Página principal con el escáner de códigos QR

### Funcionalidades del escáner:
- ✅ **Inicio automático** del escáner al cargar la página
- 🎯 **Detección automática** de códigos QR
- 📋 **Copiar al portapapeles** el contenido escaneado
- 🔗 **Abrir enlaces** automáticamente si el QR contiene una URL
- 🔦 **Linterna** (si el dispositivo lo soporta)
- 🔍 **Zoom** ajustable

## 🔧 Tecnologías utilizadas

- **HTML5** - Estructura de la aplicación
- **CSS3** - Estilos modernos con gradientes y efectos
- **JavaScript** - Funcionalidad interactiva
- **HTML5-QRCode** - Librería para el escáner QR
- **GitHub Pages** - Hosting gratuito

## 📱 Compatibilidad

- ✅ Chrome/Chromium (móvil y escritorio)
- ✅ Firefox (móvil y escritorio)
- ✅ Safari (iOS y macOS)
- ✅ Edge
- ✅ Opera

## 🔒 Privacidad

- No se almacenan datos personales
- No se envía información a servidores externos
- El procesamiento del QR es local en tu dispositivo
- No se requiere registro ni instalación

## 📞 Soporte

Si encuentras algún problema:
1. Asegúrate de que tu navegador soporte WebRTC
2. Permite el acceso a la cámara cuando se solicite
3. Usa HTTPS (GitHub Pages lo proporciona automáticamente)

---

**¡Tu escáner QR está listo para usar en GitHub Pages! 🎉**
