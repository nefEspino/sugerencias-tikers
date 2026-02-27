# 📈 Sugerencias Tickers

Herramienta de selección de acciones impulsada por IA.

## 🌐 Demo en vivo
> Disponible en: `https://TU-USUARIO.github.io/sugerencias-tickers`

## ✨ Características

- **5 estrategias**: Tech Titans, Dow Top Picks, Value Gems, Momentum, Defensivas
- **Datos en 3 capas**:
  1. 🟢 **Yahoo Finance** via proxy CORS (datos en vivo)
  2. 🔵 **Claude IA con web_search** (fallback automático)
  3. 🟡 **Datos estáticos** (último recurso)
- **Score IA** (0-100) calculado por fundamentales + momentum
- **Análisis IA por acción** al hacer clic (Claude + búsqueda web)
- **Asistente IA** para preguntas sobre el mercado
- **Top Movers** y breakdown por sectores

## 🚀 Deploy manual en GitHub Pages

1. Sube `index.html` y `README.md` a tu repo en GitHub
2. Ve a **Settings → Pages**
3. En **Source**, selecciona `Deploy from a branch` → `main` → `/ (root)`
4. Guarda — tu app estará en `https://TU-USUARIO.github.io/sugerencias-tickers`

## 🛠️ Uso local

Solo abre `index.html` en tu navegador. No requiere servidor.

## ⚠️ Disclaimer

Esta herramienta es educativa e informativa. No constituye asesoramiento financiero.

## 📦 Tech Stack

- HTML / CSS / JavaScript vanilla
- [Yahoo Finance API](https://finance.yahoo.com) via AllOrigins proxy
- [Claude API](https://anthropic.com) (claude-sonnet-4) con web_search
- Google Fonts: Space Mono + Syne
