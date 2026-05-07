# Landing — Newsletter Landing Page

An open-source, single-page newsletter landing page. Clean dark design with editorial typography. No frameworks, no build tools — just HTML and CSS.

## Preview

![Hero](https://i.imgur.com/Wmcciq8.png)
![Mobile](https://i.imgur.com/tXLM6at.png)

## Stack

- Plain HTML5 + CSS3 (no JS frameworks)
- [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) via Google Fonts
- Zero dependencies, zero build step

## Structure

```
landingpage1/
├── index.html
├── styles/
│   └── style.css       # All styles, single file
└── components/
    └── images/
        ├── Logo.svg
        ├── headerwoman.svg
        └── icons/
            └── whatsapp.svg
```

## Sections

| Section | Description |
|---|---|
| **Hero** | Headline + email subscribe form |
| **O que tem lá dentro** | Content categories with editorial numbering |
| **Edições recentes** | Horizontal-scroll archive of past issues |
| **Depoimentos** | Reader testimonials |
| **Assine** | Second call-to-action + form |
| **Footer** | Links + license |

## Usage

No setup needed. Clone and open `index.html` in a browser.

```bash
git clone https://github.com/your-user/landingpage1.git
cd landingpage1
open index.html
```

To connect the subscribe form to a real backend, replace the `form.addEventListener('submit', ...)` handlers in the `<script>` block at the bottom of `index.html`.

## Customization

All design tokens (colors, fonts, spacing) live at the top of `style.css` under `:root`:

```css
:root {
  --bg:      #09080A;
  --accent:  #FF6B1A;
  --fg:      #EAE4D9;
  /* ... */
}
```

## License

MIT — free to use, modify, and distribute.

