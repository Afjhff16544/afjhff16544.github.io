# AionForge studio website

Public studio site for **AionForge**, hosted with GitHub Pages.

**Live URL:** https://aionforgestudio.github.io

## Repository

This is an organization GitHub Pages site:

- Organization: [`AionForgeStudio`](https://github.com/AionForgeStudio)
- Repository: `AionForgeStudio.github.io`
- Source branch: `main`
- Folder: `/` (root)

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Site structure

| Path | Purpose |
|------|---------|
| `index.html` | Studio landing page |
| `projects.html` | Project status and future release pages |
| `about.html` | Studio about copy |
| `contact.html` | Contact via email |
| `press.html` | Press boilerplate and assets |
| `css/site.css` | Shared styles |
| `assets/` | Logo mark and favicon |

## Custom domain later (`aionforge.com`)

When the domain is ready:

1. Buy and configure DNS for `aionforge.com`.
2. In this repo, add a root file named `CNAME` containing:

   ```text
   aionforge.com
   ```

3. In GitHub: **Settings → Pages → Custom domain**, enter `aionforge.com`.
4. Enable **Enforce HTTPS** after DNS checks pass.

Suggested DNS records (provider-specific UI may vary):

| Type | Host | Value |
|------|------|--------|
| `A` | `@` | `185.199.108.153` |
| `A` | `@` | `185.199.109.153` |
| `A` | `@` | `185.199.110.153` |
| `A` | `@` | `185.199.111.153` |
| `CNAME` | `www` | `aionforgestudio.github.io` |

GitHub’s current Pages IP list: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Optional org rename for cleaner default URL

GitHub Pages org sites use `{org-login}.github.io`.

Today:

- Org login: `AionForgeStudio`
- Default site: `https://aionforgestudio.github.io`

If you rename the organization login to `AionForge` in GitHub org settings, then:

1. Rename this repository to `AionForge.github.io`
2. The default URL becomes `https://aionforge.github.io`

Display name can already be “AionForge” without changing the login.

## What GitHub Pages is for

Good fit:

- Landing page, project pages, screenshots/trailers
- About, contact, development updates
- Documentation and press kit
- Custom domain + HTTPS

Not a fit (static hosting):

- Server-side databases, account systems, private dashboards
- Complex backend APIs
- Native server-side form processing (use mailto, Formspree, or similar)

## Contact

Studio email: [aionforgestudios@gmail.com](mailto:aionforgestudios@gmail.com)
