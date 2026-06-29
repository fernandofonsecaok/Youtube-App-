# 🎬 YouTube Archive Pro

Buscador avanzado de videos de YouTube con colecciones, notas, canales favoritos y reproductor embebido.

## ✨ Funcionalidades

- 🔍 Búsqueda avanzada con filtros (idioma, país, duración, HD, subtítulos)
- 📁 Biblioteca de videos guardados en colecciones personalizadas
- 📝 Notas por video con tooltip preview
- 📺 Reproductor embebido (sin salir de la app)
- 👤 Canales favoritos organizados en carpetas
- 📊 Comparación de canales con métricas
- 📥 Exportar resultados a CSV
- 🌙 Modo oscuro automático

## 🚀 Cómo usar

1. Abrí la app: **[Ver app →](https://TU-USUARIO.github.io/youtube-archive)**
2. Conseguí una API Key gratuita de YouTube Data v3:
   - Entrá a [console.cloud.google.com](https://console.cloud.google.com)
   - Creá un proyecto → habilitá **YouTube Data API v3**
   - Credenciales → Crear credencial → API Key
3. Pegá tu API Key en la app y buscá

## 🔑 Nota sobre la API Key

La API Key **nunca se envía a ningún servidor externo**. Se guarda solo en tu sesión del navegador y las llamadas van directo a la API de YouTube.

## 🛠️ Tecnología

- HTML + CSS + JavaScript puro (sin frameworks, sin dependencias)
- YouTube Data API v3
- localStorage para persistencia de datos
- GitHub Pages para hosting

## 📦 Estructura

```
youtube-archive/
├── index.html   ← toda la aplicación
└── README.md
```
