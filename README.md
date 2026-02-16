# Estación Kepler

Una historia interactiva de ciencia ficción ambientada en una estación espacial en la órbita de Saturno.

## 📖 Descripción

**Estación Kepler** es una aventura narrativa de "elige tu propia aventura" creada completamente en HTML. La historia sigue a un astronauta que despierta en una estación espacial abandonada donde algo terrible ha ocurrido. A través de decisiones críticas, el jugador debe descubrir qué pasó con la tripulación y decidir su propio destino.

**URL del proyecto:** [http://bombardeen-palencia.xyz/angel/lab_3/](http://bombardeen-palencia.xyz/angel/lab_3/)

## 🎯 Características

- **Historia no lineal** con múltiples caminos y decisiones
- **3 finales diferentes** según las elecciones del jugador:
  - Evacuación (El Superviviente)
  - Quedarse (El Guardián) 
  - Descubrir la verdad (El Investigador)
- **10 escenas interactivas** distribuidas en 4 áreas temáticas
- **Navegación compleja** con loops y múltiples rutas
- **100% HTML** - Sin CSS ni JavaScript

## 📁 Estructura del Proyecto

```
lab_3/
├── index.html              # Página inicial
├── README.md              # Este archivo
├── images/                # Todas las imágenes del proyecto
│   ├── control-room.jpg
│   ├── terminal.jpg
│   ├── emergency.jpg
│   ├── escape-pods.jpg
│   ├── pod-interior.jpg
│   ├── signal-lab.jpg
│   ├── response-terminal.jpg
│   ├── evacuation.jpg
│   ├── station-alone.jpg
│   └── discovery.jpg
├── station/               # Escenas de la estación
│   ├── control.html
│   ├── communications.html
│   └── emergency.html
├── escape/                # Escenas de escape
│   ├── pods.html
│   └── decision.html
├── signal/                # Investigación de la señal
│   ├── investigate.html
│   └── response.html
└── endings/               # Los 3 finales
    ├── evacuate.html
    ├── stay.html
    └── mystery.html
```

## 🎮 Cómo Jugar

1. Visita [http://bombardeen-palencia.xyz/angel/lab_3/](http://bombardeen-palencia.xyz/angel/lab_3/)
2. Lee la escena inicial en la Estación Kepler
3. Toma decisiones haciendo clic en los links
4. Explora diferentes caminos y descubre los 3 finales posibles

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura y contenido
- **Etiquetas semánticas** - `<main>`, `<article>`, `<section>`, `<aside>`, `<nav>`, `<header>`, `<footer>`
- **Elementos interactivos** - `<details>`, `<summary>`, `<dialog>`, `<progress>`, `<time>`
- **Sin dependencias** - 100% HTML puro

## ✨ Elementos Destacados

- ✅ **Breadcrumbs** en todas las páginas para navegación clara
- ✅ **Progress bars** mostrando estado de sistemas
- ✅ **Details/Summary** para información expandible
- ✅ **Dialog modals** para alertas del sistema
- ✅ **Time elements** con timestamps precisos
- ✅ **Paths relativos y absolutos** correctamente implementados
- ✅ **Sin `<div>`** - Solo etiquetas semánticas

## 📝 Detalles Técnicos

- **Total de páginas:** 11 (1 inicio + 10 escenas)
- **Total de imágenes:** 10
- **Caminos posibles:** Múltiples rutas hacia 3 finales
- **Líneas de código:** ~1,300 líneas de HTML
- **Zero CSS/JS:** Proyecto 100% HTML puro

## 🎨 Créditos

- **Autor:** Ángel Sanabria
- **Carnet:** 2021067
- **Curso:** Desarrollo Web
- **Fecha:** Febrero 2026
- **Imágenes:** Generadas con IA (Gemini)

## 📄 Licencia

Este proyecto es un trabajo académico para el curso de Desarrollo Web.

---

**Última actualización:** 15 de febrero, 2026
