# Peru Tractor · Análisis de Flujo Comercial-Logístico

Experiencia web **interactiva de una sola página** que diagnostica el proceso de repuestos CAT/CTP: reconstruye el flujo operativo completo, identifica los cuellos de botella y propone un flujo optimizado.

> Hecho por **VERONIX**. Single-file, sin build, listo para Vercel / GitHub Pages.

## ✦ Qué incluye

- **Diagrama de flujo por carriles** (7 áreas) con nodos clicables.
- **Toggle AS-IS ↔ TO-BE**: alterna entre la operación actual y la propuesta.
- **Panel de detalle** por paso, con la recomendación de IA para cada cuello.
- **7 cuellos de botella** filtrables por severidad (crítico / alto / medio).
- **Matriz impacto–esfuerzo** interactiva (quick wins vs. grandes apuestas).
- **KPIs objetivo** animados y **hoja de ruta** en 3 fases.

## 🚀 Deploy

Todo vive en `index.html` (sin dependencias, sin paso de build).

**Vercel**
```bash
# opción 1: arrastra la carpeta en vercel.com
# opción 2: CLI
npm i -g vercel
vercel --prod
```
Vercel detecta `index.html` y lo sirve directamente.

**GitHub Pages**
1. Sube el repo.
2. *Settings → Pages → Deploy from branch → main / root*.

**Local**
```bash
python3 -m http.server 8000   # abre http://localhost:8000
```

## 🎨 Marca

Fondo `#050509` / navy · púrpura `#7B5FFF` · teal `#00FFD1` · tipografías Orbitron + Exo 2.

---

© 2026 VERONIX · Análisis de proceso para Peru Tractor.
