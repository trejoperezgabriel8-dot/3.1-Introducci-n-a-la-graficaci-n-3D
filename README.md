# Introducción a la Graficación 3D - Three.js FBX Loader

Este proyecto forma parte de la unidad de **Graficación 3D**, centrado en la carga, visualización y control de modelos tridimensionales en el navegador utilizando la librería **Three.js** y el motor de renderizado **WebGL**.

## 🎯 Objetivos de la Práctica
- Implementar un entorno 3D básico (Escena, Cámara y Luces).
- Utilizar el cargador **FBXLoader** para importar modelos con texturas y esqueletos.
- Gestionar la lógica de animación y cambio de movimientos del personaje mediante código.
- Organizar el proyecto de forma modular para su despliegue web.

## 🛠️ Tecnologías y Herramientas
- **Three.js:** Motor de gráficos 3D para JavaScript.
- **WebGL:** API nativa para renderizado de gráficos acelerados por hardware.
- **FBX Models:** Formato de intercambio de activos 3D.
- **GitHub Pages:** Hosting para la demostración en vivo.

## 📁 Estructura de Archivos
```text
threejs-3d-models/
├── index.html              # Estructura principal y contenedor del canvas
├── assets/
│   ├── js/
│   │   └── main.js         # Lógica de Three.js (Escena, Render, Animaciones)
│   ├── models/             # Archivos .fbx del personaje y animaciones
│   └── vendor/             # Librerías de Three.js y Loaders necesarios
└── README.md