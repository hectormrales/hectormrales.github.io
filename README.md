# Portafolio Personal - Héctor Morales

Sitio web personal profesional creado con HTML, CSS y JavaScript vanilla.

## 🚀 Características

- Diseño moderno y responsivo
- Animaciones suaves
- Secciones completas: Sobre mí, Proyectos, Formación, Pasatiempos, Curiosidades, Contacto y Descargas
- Optimizado para GitHub Pages
- Tema oscuro profesional
- Formulario de contacto funcional

## 📁 Estructura del Proyecto

```
hectormrales.github.io/
├── index.html          # Página principal
├── styles.css          # Estilos
├── script.js           # JavaScript
├── README.md           # Este archivo
└── assets/             # Recursos
    ├── profile.jpg     # Tu foto de perfil
    ├── cv-hector-morales.pdf  # Tu CV
    └── public-key.asc  # Tu llave pública PGP
```

## 🛠️ Instalación

1. Crea el repositorio `hectormrales.github.io` en GitHub
2. Clona el repositorio
3. Agrega los archivos proporcionados
4. Crea la carpeta `assets/` y agrega:
   - Una foto tuya como `profile.jpg`
   - Tu CV como `cv-hector-morales.pdf`
   - Tu llave pública como `public-key.asc`
5. Sube los cambios a GitHub

## 📝 Personalización

### Información Personal
Edita `index.html` y actualiza:
- Nombre y título
- Enlaces de redes sociales
- Email y ubicación
- Descripción personal
- Proyectos
- Formación académica
- Pasatiempos y curiosidades

### Formulario de Contacto
El formulario usa Formspree. Para configurarlo:
1. Ve a https://formspree.io/
2. Crea una cuenta gratis
3. Crea un nuevo formulario
4. Reemplaza `action="https://formspree.io/f/tu-id"` con tu ID

### Colores
Puedes cambiar los colores en `styles.css` editando las variables CSS:
```css
:root {
    --primary-color: #00ff88;
    --secondary-color: #0066ff;
    /* ... más colores */
}
```

## 🌐 Despliegue

1. Ve a la configuración de tu repositorio en GitHub
2. Ve a "Pages" en el menú lateral
3. En "Source", selecciona la rama `main`
4. Guarda los cambios
5. Tu sitio estará disponible en `https://hectormrales.github.io`

## 📱 Responsive

El sitio es completamente responsivo y se adapta a:
- Móviles (< 768px)
- Tablets (768px - 1024px)
- Escritorio (> 1024px)

## 🔐 Llave PGP

Para generar tu llave pública PGP para la práctica de Criptografía:

```bash
# Generar par de llaves
gpg --gen-key

# Exportar llave pública
gpg --armor --export tu-email@ejemplo.com > public-key.asc

# Ver fingerprint
gpg --fingerprint tu-email@ejemplo.com
```

Actualiza el fingerprint en la sección de descargas del `index.html`.

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo y modificarlo.

---

Hecho con ❤️ y ☕ por Héctor Morales