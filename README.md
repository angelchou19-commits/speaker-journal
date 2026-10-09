# The Speaker Journal

A personal journal for the guest speakers who visit class. Each speaker gets a profile page with a reflection: a 1–5 rating, the line I'll remember, my reflection, and how I'll apply it. An **About me** page holds my résumé.

## Files

- `index.html` is the whole site in one file (HTML, CSS and JavaScript).

## Where the data lives

The live site runs as a Claude artifact. Speakers, reflections and the résumé are saved in the artifact's database through `window.claude.use("db")`, which only works when the page is opened on claude.ai.

If you open `index.html` somewhere else (locally or on GitHub Pages), the layout loads but the data doesn't, and the page says "Open this page on claude.ai to load the journal."
