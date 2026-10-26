# drivax.github.io

Alexandre Lalance portfolio



- `https://drivax.github.io/`


- `docs/Alexandre_LALANCE_CV__eng_.pdf`: downloadable PDF CV



## Local Preview

You can preview the site with any static file server from the repository root.

Examples:

```powershell
python -m http.server 8000
```

Then open:

- `http://localhost:8000/`

## Interface styling

The shared visual rules live in `docs/interface.css`, loaded after the original
component and animation stylesheet. It defines typography, both color themes,
header sizing, cards, buttons and responsive layouts. Figures use `object-fit:
contain` so scientific axes and legends remain visible.

The introduction/projects and resume load from HTML fragments; their Markdown
copies remain available as fallbacks. Contact is the final section in `index.html`.
Navigation follows scrolling, respects reduced motion and includes a keyboard
skip link. Theme preference is saved locally when browser storage is available.
