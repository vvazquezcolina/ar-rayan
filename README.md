# Ar-Rayan - Sitio Estático

Sitio web estático exportado desde WordPress, listo para desplegar en Vercel.

## 🚀 Despliegue en Vercel

### Opción 1: Desde la interfaz web de Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión
2. Haz clic en "Add New Project"
3. Importa tu repositorio de Git (GitHub, GitLab, Bitbucket) o arrastra la carpeta del proyecto
4. Vercel detectará automáticamente que es un sitio estático
5. Haz clic en "Deploy"

### Opción 2: Desde la línea de comandos

```bash
# Instala Vercel CLI (si no lo tienes)
npm i -g vercel

# Desde la raíz del proyecto
vercel

# Para producción
vercel --prod
```

### Opción 3: Conectar repositorio Git

1. Conecta tu repositorio a Vercel
2. Cada push a la rama principal desplegará automáticamente
3. Los cambios se actualizarán en tiempo real

## 📁 Estructura del Proyecto

- `index.html` - Página principal
- `vercel.json` - Configuración de Vercel
- `robots.txt` - Configuración de robots
- `sitemap*.xml` - Sitemaps para SEO
- `wp-content/` - Contenido de WordPress (temas, plugins, uploads)
- `wp-includes/` - Archivos de WordPress

## ⚙️ Configuración

El archivo `vercel.json` incluye:
- Headers de seguridad
- Cache para archivos estáticos (imágenes, CSS, JS)
- Rewrites para rutas de WordPress

## 🔧 Personalización

### Cambiar dominio

Si necesitas actualizar el dominio en los sitemaps o robots.txt después del despliegue, puedes hacerlo desde el dashboard de Vercel o actualizando los archivos.

### Variables de entorno

No se requieren variables de entorno para este sitio estático.

## 📝 Notas

- Este es un sitio completamente estático, no requiere servidor
- Todas las rutas son relativas y funcionarán en cualquier dominio
- El sitio está optimizado para SEO con sitemaps y meta tags

