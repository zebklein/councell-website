# Ruth Tietjen Councell — Portfolio Site

Source for [councell.net](http://www.councell.net), the online portfolio of watercolor and oil painter **Ruth Tietjen Councell**. The site catalogs decades of work across galleries including watercolor abstracts, botanical art, portraits, illuminated letters, liturgical hangings, and children's book illustration.

## Stack

Static site — plain HTML, CSS, and vanilla JavaScript, no build step or framework.

- `style.css` — shared styling and responsive nav
- `slideshow.js` — lightweight image slideshow used on the home page
- `media/` — artwork images, organized by gallery/collection
- One `.html` file per gallery/archive page, sharing a common nav structure

## Running locally

No build tools required. Either open `index.html` directly in a browser, or serve the directory locally to avoid any relative-path quirks:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Structure

- `index.html` — home page
- `about.html`, `cv.html`, `teaching.html` — artist statement, CV, and teaching info
- Gallery pages (e.g. `watercolor_abstracts.html`, `collage.html`, `trees.html`, `portraits.html`, `accordion_index.html`) — current work
- Archive pages (e.g. `botanical.html`, `garden.html`, `illuminations.html`, `oil_paintings_index.html`, `liturgical_hangings.html`, `jackets.html`, `childrens_books.html`, `just_for_fun.html`) — past collections
- `media/` — all artwork and site imagery, grouped by collection

## Credits

Site designed and built by [Zeb Kleinsorge](https://www.zebklein.com).
