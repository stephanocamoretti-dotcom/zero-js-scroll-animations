<p align="right">
  <a href="./README.md">🇺🇸 Read in English</a>
</p>

<p align="center">
  <img src="./assets/banner.svg" alt="Banner de Zero-JS Scroll Animations" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CSS-Scroll_Timeline-818CF8?style=for-the-badge&logo=css3&logoColor=white" alt="CSS Scroll Timeline" />
  <img src="https://img.shields.io/badge/JavaScript-0_Bytes-34D399?style=for-the-badge" alt="0 Bytes JS" />
  <img src="https://img.shields.io/badge/License-MIT-38BDF8?style=for-the-badge" alt="Licencia MIT" />
</p>

# zero-js-scroll-animations

Patrones listos para usar de **animaciones ligadas al scroll en CSS puro** usando `animation-timeline: scroll()` y `animation-timeline: view()`, ejecutándose en el compositor GPU sin ocupar el hilo principal de JavaScript.

---

## Cómo funciona

```mermaid
flowchart LR
    Scroll["Scroll del Usuario"] --> Comp["Compositor GPU del Navegador"]
    Comp -->|"scroll root block"| Bar["Barra de progreso scaleX"]
    Comp -->|"view timeline + animation-range"| Cards["Entrada de tarjetas sin JS"]
```

---

## Inicio rápido

Abre `index.html` directamente en tu navegador o sírvelo localmente:

```bash
npx serve .
```

---

## Referencias

- [MDN Web Docs — CSS Scroll-driven Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_scroll-driven_animations)
- [Chrome for Developers — Animate Elements on Scroll with Scroll-driven Animations](https://developer.chrome.com/docs/css-ui/scroll-driven-animations)
