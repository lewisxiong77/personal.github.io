# Personal Portfolio — Original Design

An early personal portfolio by **Lewis Xiong**, built with HTML and CSS. It introduces the author, presents original visual assets, and links to his GitHub profile.

This version retains the separate portrait and decorative shape from the original design. The content reflects the original project.

## Features

- Responsive layout for phone and desktop screens.
- Working About, Gallery, and Contact section links.
- Semantic HTML, keyboard focus indicators, and text alternatives for images.
- Local images and font; no JavaScript framework or build dependencies.

## Run locally

Clone this repository and serve its root directory:

```sh
git clone https://github.com/lewisxiong77/personal.github.io.git
cd personal.github.io
python3 -m http.server 8000
```

Open http://localhost:8000. On Windows, use `py -m http.server 8000` if `python3` is unavailable.

## Repository structure

| Path | Purpose |
| --- | --- |
| `index.html` | Page content and section navigation |
| `assets/css/style.css` | Layout, typography, and responsive styles |
| `assets/images/` | Original photographs, artwork, and design exports |
| `assets/fonts/` | Existing local font |
| `docs/assets.md` | Asset rename map and maintenance notes |

## Editing

Update content in `index.html` and styling in `assets/css/style.css`.
Use lowercase, hyphenated names for new assets and update every reference when moving a file.
CSS image paths are relative to the stylesheet, so images use `../images/`.

## Validation

Before publishing, check section links, image loading, keyboard navigation, and layouts at narrow and wide viewport sizes.
To publish with GitHub Pages, configure the repository's Pages settings to serve the intended branch and root folder.

## Project scope

This is a static website project. It does not include a contact form, backend, robotics code, or C++ coursework.
Some unused design exports are retained as source artwork; see [the asset inventory](docs/assets.md).
