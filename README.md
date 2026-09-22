# 💐 Regalo Flor Amarilla — Para Mi Esposa

Regalo web animado e interativo: una carta romántica con sobre sellado que se abre al tocarlo, y al final un jardín de flores amarillas con música.

**En vivo:** https://regalos-flor-amarrilla.vercel.app/

---

## ✨ Características

- **Pantalla de inicio** con personajes emoji 👨💛👩, estrellas y el mensaje *"¿Quieres ser mi esposa por siempre?"*
- **Botones SÍ / NO** — el botón NO se esquiva de forma juguetona; el SÍ avanza al siguiente paso
- **Sobre rojo sellado (lacre con corazón)** — 1.er toque: la solapa se abre y sale el papel con la carta romántica; 2.º toque: suena la música y aparecen las flores
- **Escena final** de flores amarillas animadas (CSS), pétalos, corazones dorados y botón de música (⏸/▶)
- **Optimizado para móvil y Safari/iPhone**: menos partículas en pantallas chicas, audio que solo arranca tras un gesto del usuario (política de autoplay)

## 🛠 Tecnologías

- HTML5 + CSS3 (animaciones, `clip-path`, 3D con `perspective`)
- JavaScript vanilla (sin frameworks ni dependencias)
- Música: `Floricienta.mp3` (archivo externo, no incrustado en base64)

## 📁 Estructura

```
REGALOS-Flor-amarrilla/
├── index.html        # Toda la app: HTML + CSS + JS en un solo archivo
├── Floricienta.mp3   # Música de la escena final
└── README.md
```

## ▶️ Ejecutar localmente

No necesita build ni servidor:

```bash
git clone https://github.com/ShaggRD5/REGALOS-Flor-amarrilla.git
cd REGALOS-Flor-amarrilla
start index.html        # o ábrelo en tu navegador
```

> Para probar la música, sirve la carpeta con un servidor local (ej. `npx serve .`) en vez de `file://`.

## 🚀 Despliegue

- **Plataforma:** [Vercel](https://vercel.com) — redespliega solo con cada `git push` a la rama `Wed`
- **Rama principal:** `Wed`
- **Repo:** https://github.com/ShaggRD5/REGALOS-Flor-amarrilla

## 📱 Uso

1. Comparte el link con quien quieras sorprender
2. Toca **SÍ**
3. Toca el sobre → se abre y aparece la carta
4. Toca de nuevo → suenan las flores 🌻 y la música

---

⚠️ **Uso personal / regalo** — solo úsalo sabiamente.
