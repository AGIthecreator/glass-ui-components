# 🎨 Modern UI Components Library

Colección premium de componentes de interfaz de usuario con estética **Glassmorphism** y **Neo-UI**.  
Enfocado en alto impacto visual y rendimiento mediante **CSS3 puro**.  
Librería de componentes de **Abel González** diseñada para interfaces modernas, elegantes y responsivas.

---

## 🧠 Stack Tecnológico

- HTML5 — estructura semántica limpia
- CSS3 — variables, keyframes y efectos visuales avanzados
- Diseño 100% responsivo

## 📂 Estructura y Uso

El proyecto está organizado de forma atómica para facilitar su implementación:
* `index.html`: Contenedor principal y estructura de los componentes.
* `styles.css`: Definición de variables globales y estilos de diseño.
* `assets/`: Recursos visuales y multimedia.

### Guía rápida de uso:
1. **Variables**: Copia el bloque `:root` en tu archivo CSS para mantener la paleta de colores.
2. **HTML**: Selecciona el componente deseado (ej. `profile-card`) y pégalo en tu estructura.
3. **Rutas**: Verifica que las rutas de imágenes en el HTML coincidan con tu carpeta de assets.
---

## ⚙️ Configuración CSS

```css
:root {
  --primary-glow: #007bff;
  --secondary-glow: #00ff88;
  --dark-bg: #0b0f1a;
  --glass-effect: rgba(255, 255, 255, 0.05);
  --glass-border: rgba(255, 255, 255, 0.1);
  --text-main: #ffffff;
}
```

---

## 🧩 Ejemplo de Componente HTML

```html
<div class="profile-card">
  <img src="https://avatars.githubusercontent.com/u/253378828?v=4" class="profile-image" alt="Abel González">
  <div class="profile-info">
    <h2>Abel González</h2>
    <p>Frontend Developer</p>
    <button class="btn-contact">Contactar</button>
  </div>
</div>
```

---

## 👨‍💻 Autor

**Abel González**  
Full Stack Developer / UI Designer  

🔗 **GitHub**: → https://github.com/AGIthecreator  

Proyecto optimizado para navegadores modernos.  
Si te sirve, ¡dale una ⭐!
