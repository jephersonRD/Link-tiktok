# 🔗 Enlaces - Jepherson RD

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)

**Una página de enlaces moderna, animada y totalmente responsive**

[Ver Demo](#) • [Reportar Bug](https://github.com/jephersonRD/enlaces/issues) • [Solicitar Feature](https://github.com/jephersonRD/enlaces/issues)

</div>

---

## ✨ Características

- 🎨 **Diseño Moderno** - Interfaz glassmorphism con gradientes animados
- 💫 **Animaciones Suaves** - Efectos visuales optimizados y fluidos
- 📱 **Totalmente Responsive** - Perfecto en móviles, tablets y desktop
- ⚡ **Alto Rendimiento** - Optimizado para carga rápida
- ♿ **Accesible** - Cumple con estándares WCAG
- 🌙 **Tema Oscuro** - Diseño elegante con colores vibrantes
- 🎯 **SEO Optimizado** - Meta tags completos para redes sociales
- 🔄 **Partículas Animadas** - Sistema de partículas flotantes optimizado

## 🖼️ Preview

```
┌─────────────────────────────────────┐
│                                     │
│         [Avatar Animado]            │
│                                     │
│        Jepherson RD                 │
│   ✨ Creador · Programador          │
│                                     │
│  ┌─────────────┐ ┌─────────────┐  │
│  │   GitHub    │ │  YouTube    │  │
│  └─────────────┘ └─────────────┘  │
│                                     │
│  ┌─────────────┐ ┌─────────────┐  │
│  │  Instagram  │ │   TikTok    │  │
│  └─────────────┘ └─────────────┘  │
│                                     │
│      [📋 Copiar Email]              │
│                                     │
└─────────────────────────────────────┘
```

## 🚀 Inicio Rápido

### Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/jephersonRD/enlaces.git
   ```

2. **Navega al directorio**
   ```bash
   cd enlaces
   ```

3. **Abre el archivo HTML**
   - Simplemente abre `index.html` en tu navegador
   - O usa Live Server en VS Code para desarrollo

### Personalización

#### Cambiar Enlaces Sociales

Edita las URLs en el HTML:

```html
<!-- GitHub -->
<a href="https://github.com/TU_USUARIO">

<!-- YouTube -->
<a href="https://youtube.com/@TU_CANAL">

<!-- Instagram -->
<a href="https://instagram.com/TU_PERFIL">

<!-- TikTok -->
<a href="https://tiktok.com/@TU_USUARIO">
```

#### Cambiar Email

Modifica la variable en el JavaScript:

```javascript
const email = 'tuemail@example.com';
```

#### Personalizar Colores

Cambia las variables CSS en `:root`:

```css
:root{
  --accent-1: #ff6b6b;  /* Color primario */
  --accent-2: #7c5cff;  /* Color secundario */
  --accent-3: #4ecdc4;  /* Color terciario */
}
```

## 🎨 Características de Diseño

### Animaciones Incluidas

| Animación | Descripción |
|-----------|-------------|
| 🌊 **Background Shift** | Fondo con gradientes animados |
| ✨ **Shimmer Effect** | Efecto de brillo en tarjetas |
| 💫 **Floating Particles** | Partículas flotantes optimizadas |
| 🎭 **Glow Pulse** | Pulso de luz en la tarjeta principal |
| 🎪 **Avatar Float** | Avatar con movimiento flotante |
| 🌈 **Gradient Rotate** | Borde del avatar con gradiente rotativo |
| 📝 **Text Gradient** | Texto con gradiente animado |
| 🎯 **Hover Effects** | Efectos interactivos en enlaces |

### Responsive Breakpoints

```css
📱 Móvil pequeño:  < 480px
📱 Móvil:          481px - 640px
📱 Tablet:         641px - 1024px
💻 Desktop pequeño: 1025px - 1280px
🖥️  Desktop grande:  > 1281px
```

## ⚙️ Optimizaciones

### Rendimiento

- ✅ Partículas reducidas de 30 a 20
- ✅ Pausa de animaciones cuando la pestaña no está visible
- ✅ Uso de `will-change` para animaciones suaves
- ✅ Lazy loading de imágenes
- ✅ CSS optimizado con GPU acceleration

### Accesibilidad

- ♿ Semántica HTML5 correcta
- ♿ ARIA labels en enlaces
- ♿ Focus visible para teclado
- ♿ Respeto a `prefers-reduced-motion`
- ♿ Contraste de colores WCAG AA

### SEO

- 🔍 Meta tags completos
- 🔍 Open Graph para redes sociales
- 🔍 Twitter Cards
- 🔍 Favicon personalizado
- 🔍 Descripciones optimizadas

## 📦 Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y animaciones
- **Tailwind CSS** - Framework CSS vía CDN
- **JavaScript ES6** - Interactividad
- **SVG** - Iconos vectoriales

## 🌐 Navegadores Compatibles

| Navegador | Versión Mínima |
|-----------|----------------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Opera | 76+ |

## 📱 Características Mobile

- ✅ Touch-friendly con áreas táctiles grandes
- ✅ Sin efectos hover en touch devices
- ✅ Optimizado para landscape mode
- ✅ Funciona sin conexión (excepto Tailwind CDN)

## 🛠️ Estructura del Proyecto

```
enlaces/
│
├── index.html          # Archivo principal
├── README.md           # Este archivo
└── assets/             # (opcional)
    └── images/
        └── avatar.jpg  # Tu avatar personalizado
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add: nueva característica'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Changelog

### v1.0.0 (2025-11-01)
- ✨ Lanzamiento inicial
- 🎨 Diseño glassmorphism
- 💫 Sistema de partículas animadas
- 📱 Diseño responsive completo
- ⚡ Optimizaciones de rendimiento
- ♿ Mejoras de accesibilidad

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👤 Autor

**Jepherson RD**

- GitHub: [@jephersonRD](https://github.com/jephersonRD)
- YouTube: [@Jeph_RD](https://www.youtube.com/@Jeph_RD)
- Instagram: [@jepherson_medina](https://www.instagram.com/jepherson_medina)
- TikTok: [@jepherson_rd](https://www.tiktok.com/@jepherson_rd)
- Email: jephersonmedina69@gmail.com

## 🌟 Muestra tu Apoyo

Si este proyecto te fue útil, ¡dale una ⭐ en GitHub!

---

<div align="center">

**Hecho con ❤️ y mucho ☕**

[⬆ Volver arriba](#-enlaces---jepherson-rd)

</div>
