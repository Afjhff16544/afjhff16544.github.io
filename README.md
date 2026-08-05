# AionForge studio website

Public studio site for **AionForge**, hosted with GitHub Pages.

**Live URL:** https://aionforgestudio.github.io

## Design language

Pulled from real studio Minecraft work:

| Layer | Look | Source |
|-------|------|--------|
| Character / brand | Cream parchment, lavender, cyan glow eyes, olive + cloth blue | Mascot face + hero portrait |
| Product | Soft studio gradients, isometric cube gear | Trailbound / Vanguard pack renders |
| Epic | Void dark, cyan + amber signal lights | Boss / creature marketing stills |
| UI chrome | Soft glass panels, purple primary, cyan accents | Site CSS tokens |

### Brand tokens (`css/site.css`)

- Cream / parchment backgrounds
- Purple (`#7b5ea7` / `#4e3a72`) primary actions
- Cyan (`#3ec8ff`) glow accents and dark-section kickers
- Space Grotesk + Outfit typography

## Local preview

```bash
python3 -m http.server 8080
```

Visit http://localhost:8080

## Site structure

| Path | Purpose |
|------|---------|
| `index.html` | Landing with hero banner, product grid, epic feature |
| `projects.html` | Project slate with product media |
| `about.html` | Studio story |
| `contact.html` | Email contact |
| `press.html` | Boilerplate + downloadable marks |
| `assets/brand/` | Pixel mascot face |
| `assets/gallery/` | Hero, product, epic stills |
| `assets/packs/` | Production pack icons |
| `css/site.css` | Design system |

## Custom domain later (`aionforge.com`)

1. Add a root `CNAME` file containing `aionforge.com`
2. GitHub → Settings → Pages → Custom domain
3. Point DNS A records to GitHub Pages IPs
4. Enable **Enforce HTTPS** after verification

## Contact

Studio email: [aionforgestudios@gmail.com](mailto:aionforgestudios@gmail.com)
