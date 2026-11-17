# Raquel Teruel: Spanish lessons

The website of Raquel Teruel, a Spanish teacher (ELE) and official DELE examiner.

- Test address: https://rachel.geiser.cloud
- Plain static HTML and CSS, served by GitHub Pages from `main`. No build step, no cookies, no trackers and no requests to other sites.
- English lives at `index.html`, Spanish at `es/index.html`. The legal page is `legal.html` / `es/legal.html`.

## Test phase

Three designs are online so Raquel can pick one:

| Option | Look | Address |
|---|---|---|
| 1 | Cuaderno cálido: cream, terracotta, handwritten name, polaroid | https://rachel.geiser.cloud/ |
| 2 | Elegancia sobria: near black and white, classic serif | https://rachel.geiser.cloud/opcion-2/ |
| 3 | Mediterráneo luminoso: sand, sea blue, coral | https://rachel.geiser.cloud/opcion-3/ |

Once she picks, the chosen design moves to the root and the other two are deleted. Every page carries `noindex` and `robots.txt` blocks crawlers until launch.

## Before launch

- Her logo, photo, prices, booking link (Cal.com), payment links (Stripe) and contact channel.
- The legal notice: full name, NIF, address and email (LSSI art. 10).
- Absolute `hreflang` URLs on her own domain, remove `noindex` and the `robots.txt` block, and update `CNAME`.

## Editing

To change a text or a price, edit the HTML and push to `main`. The site updates in about a minute. Prices appear once per language page: change both `index.html` and `es/index.html`.
