# 🖼️ IMG-KLASSO - CDN de Imágenes

Repositorio para alojar imágenes usando GitHub + jsDelivr como CDN gratuito.

## 📋 Cómo usar las imágenes

### Estructura de URL
```
https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/[nombre-imagen]
```

### Ejemplos de uso

#### En HTML
```html
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/logo.png" alt="Logo">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/banner.jpg" alt="Banner">
```

#### En CSS
```css
.hero-section {
  background-image: url('https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/hero-bg.jpg');
}

.icon {
  content: url('https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/icon.svg');
}
```

#### En Markdown
```markdown
![Alt text](https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/imagen.jpg)
```

### Ejemplos de uso en React/JavaScript
```jsx
// Componente con iconos
const Navigation = () => {
  return (
    <div>
      <img 
        src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/klasso-logo.png" 
        alt="Klasso Logo" 
        className="logo"
      />
      <button>
        <img 
          src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/flecha anterior.png" 
          alt="Anterior" 
        />
      </button>
    </div>
  );
};

// Array de imágenes para carousel
const imagenesInicio = [
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-1.png',
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-2.png',
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-3.png',
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-4.png',
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-5.png',
  'https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-6.png'
];
```

## 📁 Estructura actual del repositorio

```
images/
├── Eventos/
├── iconos/
│   ├── Group-1.png
│   ├── Group.png
│   ├── aula.png
│   ├── avisos.png
│   ├── flecha anterior.png
│   ├── flecha siguiente.png
│   ├── formkit-instagram.png
│   ├── graficas-recursos.png
│   ├── horarios.png
│   ├── klasso-logo.png
│   ├── notificar-inasistencia.png
│   ├── prime-twitter.png
│   └── recursos-matematica.png
├── inicio/
│   ├── img-itsp-1.png
│   ├── img-itsp-2.png
│   ├── img-itsp-3.png
│   ├── img-itsp-4.png
│   ├── img-itsp-5.png
│   ├── img-itsp-6.png
│   └── logo-klasso.png
├── salidas-didacticas/
│   ├── salida-1.png
│   ├── salida-2.png
│   ├── salida-3.png
│   ├── salida-4.png
│   ├── salida-5.png
│   ├── salida-6.png
│   ├── salida-7.png
│   ├── salida-8.png
│   └── salida-9.png
├── Vista-adscripcion/
│   ├── adscipcion-1.png
│   ├── adscipcion-2.png
│   ├── adscipcion-3.png
│   ├── adscipcion-4.png
│   ├── adscipcion-5.png
│   └── adscipcion-6.png
└── vista-docentes/
    ├── docente-1.png
    ├── docente-2.png
    ├── docente-3.png
    ├── docente-4.png
    ├── docente-5.png
    └── docente-6.png
```

## ⚡ Ventajas

- ✅ **Gratuito** - Sin costos ni límites
- ✅ **CDN Global** - Carga rápida mundial
- ✅ **Sin configuración** - Usar directamente las URLs
- ✅ **Control total** - Administras tus propias imágenes
- ✅ **URLs permanentes** - No se rompen los enlaces
- ✅ **Respaldo automático** - GitHub mantiene tu historial

## 📝 Mejores prácticas

### Nomenclatura de archivos
- ✅ `logo-principal.png`
- ✅ `banner-home.jpg` 
- ✅ `icon-menu.svg`
- ❌ `Logo Principal.png`
- ❌ `banner home!.jpg`

### Formatos recomendados
- **PNG**: Logos, iconos, imágenes con transparencia
- **JPG**: Fotografías, banners, imágenes con muchos colores
- **SVG**: Iconos, gráficos vectoriales
- **WebP**: Versión optimizada para web moderna

### Tamaños sugeridos
- **Logos**: 200x200px o proporcional
- **Banners**: 1920x1080px o 1200x600px
- **Iconos**: 24x24px, 32x32px, 64x64px
- **Thumbnails**: 300x300px

## 🔗 URLs CDN completas por categoría

### 📁 Iconos
```html
<!-- Logos principales -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/klasso-logo.png" alt="Klasso Logo">

<!-- Iconos funcionales -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/aula.png" alt="Aula">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/avisos.png" alt="Avisos">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/horarios.png" alt="Horarios">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/notificar-inasistencia.png" alt="Notificar Inasistencia">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/graficas-recursos.png" alt="Gráficas Recursos">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/recursos-matematica.png" alt="Recursos Matemática">

<!-- Navegación -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/flecha anterior.png" alt="Flecha Anterior">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/flecha siguiente.png" alt="Flecha Siguiente">

<!-- Redes sociales -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/formkit-instagram.png" alt="Instagram">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/prime-twitter.png" alt="Twitter">

<!-- Grupos -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/Group.png" alt="Group">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/iconos/Group-1.png" alt="Group 1">
```

### 🏠 Inicio
```html
<!-- Logo principal -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/logo-klasso.png" alt="Logo Klasso">

<!-- Imágenes ITSP -->
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-1.png" alt="ITSP 1">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-2.png" alt="ITSP 2">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-3.png" alt="ITSP 3">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-4.png" alt="ITSP 4">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-5.png" alt="ITSP 5">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/inicio/img-itsp-6.png" alt="ITSP 6">
```

### 🎯 Salidas Didácticas
```html
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-1.png" alt="Salida 1">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-2.png" alt="Salida 2">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-3.png" alt="Salida 3">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-4.png" alt="Salida 4">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-5.png" alt="Salida 5">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-6.png" alt="Salida 6">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-7.png" alt="Salida 7">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-8.png" alt="Salida 8">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/salidas-didacticas/salida-9.png" alt="Salida 9">
```

### 📋 Vista Adscripción
```html
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-1.png" alt="Adscripción 1">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-2.png" alt="Adscripción 2">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-3.png" alt="Adscripción 3">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-4.png" alt="Adscripción 4">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-5.png" alt="Adscripción 5">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/Vista-adscripcion/adscipcion-6.png" alt="Adscripción 6">
```

### 👨‍🏫 Vista Docentes
```html
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-1.png" alt="Docente 1">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-2.png" alt="Docente 2">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-3.png" alt="Docente 3">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-4.png" alt="Docente 4">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-5.png" alt="Docente 5">
<img src="https://cdn.jsdelivr.net/gh/Memy16/img-klasso@main/images/vista-docentes/docente-6.png" alt="Docente 6">
```

## 🔄 Cache y actualizaciones

- **URLs con `@main`**: Se actualizan automáticamente (cache ~24h)
- **URLs con hash específico**: Cache permanente para máximo rendimiento

## 📞 Soporte

¿Problemas con las imágenes?
1. Verifica que el archivo exista en el repositorio
2. Revisa que la URL esté bien escrita
3. Espera unos minutos para que jsDelivr actualice el cache

---

**💡 Tip**: Guarda este repositorio en marcadores para acceso rápido a tus imágenes.

## 🌟 Créditos

Powered by:
- [GitHub](https://github.com) - Almacenamiento
- [jsDelivr](https://jsdelivr.com) - CDN global
