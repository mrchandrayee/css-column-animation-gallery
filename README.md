# CSS Column Animation Gallery

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-column-animation-gallery/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable recreation of the four CSS column effects visible in the 13.3-second screen recording.

## Included animations
1. **Fade Animation** — columns fade in while rising from `translateY(50px)`.
2. **Slide Animation** — columns slide in from `translateX(-80px)`.
3. **Flip Animation** — columns rotate from `rotateY(90deg)` to their front view.
4. **Wave Animation** — columns continuously move up and down with staggered delays.

## Run locally
No dependencies or build tools are needed.

```bash
python -m http.server 8000
```

Open http://localhost:8000.

## Files
- `index.html` — four demo cards and visible CSS snippets
- `style.css` — gradients, layout, keyframes, staggered delays and responsive styles

## Source extraction note
The screen recording visibly labels the four effects as Fade Animation, Slide Animation, Flip Animation, and Wave Animation. The readable code snippets include:
- Fade: `opacity: 0`, `transform: translateY(50px)`, `animation: fadeUp 0.6s forwards`
- Slide: `transform: translateX(-80px)`, `opacity: 0`, `animation: slideIn 0.5s forwards`
- Flip: `transform: rotateY(90deg)`, `animation: flipIn 0.6s forwards`
- Wave: `animation: wave 1s infinite`

The rest of the CSS keyframes, delays, markup and responsive layout are reconstructed to make each displayed effect work as a complete standalone demo. The video does not expose a JavaScript file; none is required for these CSS-only animations.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
