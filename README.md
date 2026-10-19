# DocTzok.github.io

Personal academic website of Alexandros Tzanakakis: https://doctzok.github.io

It's plain HTML and CSS, with no build step.

## Files

| File | What it is |
|---|---|
| `index.html` | All page content: about, news, research, publications, experience, education |
| `style.css` | Styling, with light and dark mode |
| `assets/profile.jpg` | Profile photo |
| `assets/Tzanakakis_CV.pdf` | CV linked from the "Download CV" button (phone number and home address removed) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Common edits

**Add a news item.** In `index.html`, copy one `<li>` inside `<ul class="news">` and paste it at the top of the list:

```html
<li>
  <time datetime="2026-11-19">Nov 19, 2026</time>
  <span>Received an AGBT Next Gen Leadership Award!</span>
</li>
```

**Add a publication.** Copy one `<li>` inside `<ol class="pubs">`. Put your name in `<span class="me">…</span>` so it's highlighted.

**Update the CV.** Replace `assets/Tzanakakis_CV.pdf` with the new file, keeping the same file name.

You can make all of these edits directly on github.com: open the file, click the pencil icon, edit, then commit. The site updates in about a minute.
