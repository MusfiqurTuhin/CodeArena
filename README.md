# CodeArena

A static front-end prototype for "CodeArena", a planned learning website for university-level computer science students in Bangla. The repository also holds the brand identity files.

## What it does

The site code is in `Website/`. The home page says CodeArena aims to give CSE students learning resources in the Bangla language. It has these parts:

- `index.html`: landing page with navigation (Home, Courses, Library, Live Reading, Download Books, Q&A), an About section, contact forms and a newsletter form.
- `login.html`: login and registration forms. The login form just links to `index.html`; there is no authentication code.
- `subjects/computer_courses.html`: a stub page titled "Computer Science Courses on CodeArena" with navigation only.

There is no backend, so no course, library or Q&A functionality exists in this repository. The contact forms use `mailto:` actions.

## Tech stack

- HTML, CSS and JavaScript
- jQuery loaded from a CDN

## Folder layout

```
Website/                  the site (pages, style.css, loginStyle.css, script.js, images)
Website/subjects/         subject pages
logo*.png, logo.jpg, logo.ai       logo files
CodeArena Visual Brand Identity Guidelines.ai / .pdf   brand guidelines
```

## Run

There is no build step or package manifest. Open `Website/index.html` in a browser, or serve the `Website/` folder with any static file server. An internet connection is needed for jQuery.

## Environment variables

None.

## Status

An early prototype. Several pages are placeholders and the site has no tests.
