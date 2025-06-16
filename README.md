# 💻 Frontend - Gestión de Clientes - Concesionario Nation

Este es el frontend del sistema de gestión de clientes desarrollado para **Nation**, una plataforma creada para facilitar campañas de marketing enfocadas en la venta de neumáticos, permitiendo una segmentación inteligente de clientes basada en datos de uso.

---

## 🌟 Características principales

- Interfaz intuitiva para buscar y filtrar clientes por:
  - Kilometraje del vehículo
  - Sucursal
  - Patente u otros datos clave
- Bloqueo visual de clientes ya consultados por otros usuarios (en tiempo real)
- Diseño responsivo con estilo profesional
- Conexión WebSocket con el backend para actualización sin recarga
- Tailwind CSS para estilos rápidos y modernos

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3 + Tailwind CSS**
- **JavaScript Vanilla**
- **WebSocket**
- **Netlify** (deploy)

---

## 📁 Estructura del proyecto

```bash
frontNation-main/
├── index.html            # Página principal
├── scripts/
│   └── app.js            # Lógica del frontend y WebSocket
├── styles/
│   ├── styles.css        # Estilos personalizados
│   └── tailwind.css      # Estilos base de Tailwind
├── img/                  # Logos e imágenes
```

---

## 🚀 ¿Cómo usarlo?

1. Clona el repositorio y accede a la carpeta:

```bash
git clone https://github.com/tu-usuario/frontNation.git
cd frontNation-main
```

2. Ejecuta un servidor local, por ejemplo con `live-server`:

```bash
live-server
```

3. Asegúrate de que el backend esté corriendo y que la URL esté correctamente apuntada en `scripts/app.js`.

4. También puedes visitar la versión desplegada:

🔗 [https://gestionclientessa.netlify.app](https://gestionclientessa.netlify.app)

---

## 🧠 Notas del desarrollador

Este proyecto fue desarrollado completamente por mí, como parte de una solución para una campaña de marketing real del concesionario **Nación**. El frontend representa un gran aprendizaje y dedicación, integrando lógica de negocio, experiencia de usuario y comunicación en tiempo real.

Fue un reto técnico que me dio muchas alegrías y me ayudó a consolidar habilidades tanto de desarrollo como de diseño enfocado al usuario.

---
