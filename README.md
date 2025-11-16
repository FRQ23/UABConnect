# UABConnect

Propuesta académica para crear la primera universidad acreditada en el metaverso. Este repositorio contiene el sitio informativo del proyecto, construido sobre una plantilla responsiva de Bootstrap y personalizado con la narrativa del equipo de estudiantes de la Facultad de Ciencias Químicas e Ingeniería de la UABC.

## ✨ Características principales
- **Historia completa del proyecto**: secciones de visión, tecnología, financiamiento, impacto y FAQ.
- **Switch de idioma (ES/EN)** basado en `localStorage` y atributos `data-translate`.
- **Diseño responsivo** con Bootstrap 5, íconos de Bootstrap Icons y tipografías de Google Fonts.
- **Contenido estático optimizado** listo para desplegarse en GitHub Pages u otro hosting estático.

## 🗂 Estructura del repositorio
```
UABConnect/
├── index.html              # Página principal
├── topics-listing.html     # Vista extendida del proyecto
├── topics-detail.html      # Detalle de cada tarjeta
├── contact.html            # Formulario/contacto alterno
├── css/                    # Bootstrap, íconos y estilos personalizados
├── js/                     # Bootstrap bundle, jQuery, scripts de interacción
├── images/                 # Imágenes del sitio (banner, tarjetas, etc.)
└── fonts/                  # Tipografías locales cuando aplica
```

## 🛠️ Requisitos
No se necesita backend ni compilación: basta un navegador moderno. Para editar se recomienda cualquier editor (VS Code, etc.).

## 🚀 Ejecutar en local
1. Clona el repositorio.
2. Abre `index.html` en tu navegador o, si prefieres un servidor local:

```powershell
# Windows PowerShell
cd C:\ruta\a\UABConnect
Start-Process msedge.exe index.html
```

También puedes usar un servidor estático (por ejemplo `npx serve` o la extensión "Live Server" de VS Code) para habilitar recarga automática.

## 🌐 Despliegue en GitHub Pages
1. Sube/actualiza el repositorio en GitHub (`main` o `master`).
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige la rama principal y la carpeta `/ (root)`.
4. Guarda; GitHub generará una URL como `https://<usuario>.github.io/UABConnect/`.
5. Cada `git push` al branch configurado rehace el despliegue automáticamente.

*Custom domain:* opcional. Si compras un dominio, agrega el registro CNAME hacia `<usuario>.github.io` y crea un archivo `CNAME` con el dominio dentro del repositorio.

## 📫 Contacto
- Instagram: [@uabconnect.21](https://www.instagram.com/uabconnect.21?igsh=MWM5bjIwNndsaDFoZQ==)
- Email: [uabconnect.21@gmail.com](mailto:uabconnect.21@gmail.com)

¡Gracias por apoyar esta propuesta académica! Si detectas mejoras o deseas contribuir, abre un issue o pull request.
