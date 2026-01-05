# DAIMUZ HAPPY - Landing Page

## 📋 Descripción del Proyecto

**DAIMUZ HAPPY** es una landing page de producto para venta de vaporizadores. El proyecto es un sitio estático HTML/CSS listo para desplegarse en **DigitalOcean App Platform**.

---

## 🏗️ Estructura del Proyecto

```
indexdaimuz/
├── index.html              # Landing page principal del producto
├── checkout.html           # Página de checkout/finalizar compra
├── package.json            # Configuración de Node.js para DigitalOcean
├── README.md               # Este archivo
└── public/
    ├── image/              # Imágenes del producto
    └── video/              # Videos del producto
```

### Páginas del Sitio

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Landing page principal con información del producto DAIMUZ HAPPY |
| `checkout.html` | Formulario de checkout para finalizar compras |

---

## 🌐 Despliegue en DigitalOcean App Platform

### package.json - Configuración del Servidor

```json
{
  "name": "daimuz-happy-landing",
  "version": "1.0.0",
  "scripts": {
    "start": "npx serve .",
    "build": "echo 'No build step required'"
  },
  "dependencies": {
    "serve": "^14.2.0"
  },
  "engines": {
    "node": ">=18.0.0"
  }
}
```

### Pasos para Desplegar

1. **Subir a GitHub**
   ```bash
   git add .
   git commit -m "Preparar para DigitalOcean"
   git push origin main
   ```

2. **Crear App en DigitalOcean**
   - Ir a [cloud.digitalocean.com/apps](https://cloud.digitalocean.com/apps)
   - Click en "Create App"
   - Conectar el repositorio de GitHub
   - DigitalOcean detectará automáticamente Node.js

3. **Configuración**
   | Parámetro | Valor |
   |-----------|-------|
   | **Build Command** | `npm run build` |
   | **Run Command** | `npm start` |
   | **Región** | NYC o la más cercana |

---

## 🖥️ Desarrollo Local

```bash
# Instalar dependencias
npm install

# Iniciar servidor
npm start

# Abrir en navegador
# http://localhost:3000
```

---

## 💡 Características

- **Producto:** DAIMUZ HAPPY Combo Completo - $90.000 COP
- **Diseño:** Responsive con Tailwind CSS
- **Checkout:** Integrado con WhatsApp para pedidos
- **Videos:** Autoplay de demostración del producto

---

## 📞 Contacto

- **WhatsApp:** [Enlace directo](https://wa.me/message/56AISNOZMVW5N1)

---

*Última actualización: Enero 2026*