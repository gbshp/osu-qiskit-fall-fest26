# Qiskit Fall Fest @ The Ohio State

Website for Qiskit Fall Fest at The Ohio State University.

## Structure

Plain static HTML/CSS/JS.

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
- **Registration link** — `register.html` currently points to a placeholder Google Form URL. Need to add a google form
- **Schedule** — Need to fill in the actual schedule.
- **Organizer names/roles** — `Need to add actual images and names of the team members`
- **Workshop materials links** — `resources.html`, once slides/notebooks are ready
- **Contact email** — currently `qiskitfallfest@osu.edu` as placeholder in the footer; need to update

