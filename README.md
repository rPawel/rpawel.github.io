# profimedia.co.uk

Static website for Profimedia, hosted on GitHub Pages at <https://www.profimedia.co.uk>.

Plain HTML and CSS. There is no build step and no JavaScript.

| Path | Purpose |
| --- | --- |
| `index.html` | Home page (services, about, approach, FAQ, contact) |
| `privacy.html` | Privacy notice |
| `404.html` | Not-found page (served automatically by GitHub Pages) |
| `assets/css/style.css` | Styles |
| `assets/img/` | Logo, Open Graph image, PWA icons |
| `robots.txt`, `sitemap.xml` | SEO. Update `<lastmod>` when content changes |

To preview locally, run `python3 -m http.server 8000` and open <http://localhost:8000>.

## Credits

- [Inter](https://rsms.me/inter/) typeface, SIL Open Font License 1.1 (`assets/fonts/OFL.txt`).
- UI icons adapted from [Lucide](https://lucide.dev), ISC License.
