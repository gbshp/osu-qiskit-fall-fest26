# Qiskit Fall Fest @ Ohio State

Website for Qiskit Fall Fest at The Ohio State University.

## Structure

Plain static HTML/CSS/JS — no build step required.

```
.
├── index.html         # Home page
├── schedule.html       # Event schedule
├── register.html       # Registration / RSVP + FAQ
├── team.html            # Organizers + sponsors
├── resources.html      # Workshop materials + learning links
├── css/style.css        # All site styling
├── js/main.js            # Nav toggle + active-link highlighting
└── .nojekyll              # Tells GitHub Pages to skip Jekyll processing
```

## Local preview

No build tools needed — just open `index.html` in a browser, or serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Things to fill in before launch

Search the codebase for `TODO` comments — they mark placeholder content that needs real info:

- **Event date & location** — currently "TBD" in `index.html` and `schedule.html`
- **Registration link** — `register.html` currently points to a placeholder Google Form URL
- **Speaker names** — `schedule.html` guest talk slot
- **Organizer names/roles** — `team.html`
- **Sponsor logos** — replace the dashed placeholder boxes in `team.html` with real `<img>` tags once sponsors are confirmed
- **Workshop materials links** — `resources.html`, once slides/notebooks are ready
- **Contact email** — currently `qiskitfallfest@osu.edu` in the footer of every page; update if you're using a different address


## Editing content

Each page is standalone HTML with the header/nav and footer duplicated at the top/bottom — edit the content in between. Shared styles live in `css/style.css` (colors are defined as CSS variables at the top of the file).
