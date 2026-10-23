# CV page

Nicolai Sikora's CV, in English and Norwegian, published with GitHub Pages at
https://nicosik.github.io/CV_page/.

It is a single static page: `index.html`, `style.css` and the images in `images/`. There is no
build step.

## Design

The page is typeset like the PDF version of the CV: a serif text face (Source Serif 4), ruled
section headings, and a rectangular portrait. IBM Plex Mono is used only for small labels such as
dates, section numbers and figure captions. There is one accent colour.

- A numbered contents list sits in the left margin on wide screens and marks the section you are
  reading.
- Each project has a figure with a numbered caption. Click an image to open it larger, then use
  the arrow keys to move between figures and Esc to close.
- Projects can be filtered by programming language. A skill that a project uses is underlined in
  the Skills list, and clicking it shows those projects.
- Language (EN/NO) and theme (light/dark) are switched in the top right. Both choices are kept in
  the browser. The theme follows the system setting until you pick one.
- Printing gives a plain version without images or controls.

## Editing

Every piece of text exists twice, marked `data-l="en"` and `data-l="nb"`. Only the active
language is shown. Edit both when you change something.

- **A project:** copy an `<article class="project">` block. List the technologies in its
  `data-tags` attribute, separated by `|`. A tag that matches a skill name connects the two.
- **Project images:** put them in `images/projects/` and reference them from the project's
  `<figure>`. The `alt` text is the caption in the enlarged view. Two images in one figure are
  shown as a pair.
- **Portrait:** `images/portrait.jpg` (4:5) is shown on the page. `CV_picture.jpg` is used for link
  previews.
- **Colours and fonts:** the variables at the top of `style.css`, with a `[data-theme="dark"]`
  block for the dark theme.

## Image credits

`images/projects/warden.jpg` is the logo of [Warden](https://github.com/BlastBlastBlast/Warden_public)
by Lars Wien Tynes, MIT licence. The other project images are screenshots from the projects or
sketches made for this page. Their captions say which is which.
