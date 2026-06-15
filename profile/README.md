# Orenji Project

![Orenji logo](https://raw.githubusercontent.com/Orenji-Project/orenji-fitness-app/main/assets/logo.png "Orenji logo")

Welcome to the Orenji Project — an ecosystem of small web applications created as part of a student portfolio (PAF) to demonstrate front-end development skills. The organization contains multiple independent, mostly static web apps that share a lightweight design system in the Orenji-core repository.

This README reflects the current development state of the organization (June 2026). The project is actively in development.

---

## Project overview

Orenji is a collection of small, focused web applications (study tools, fitness tracker, recipes, and utilities) built primarily with HTML, CSS and JavaScript. Each application is its own repository so features can be developed and showcased independently while sharing common design tokens and assets in Orenji-core.

The apps are student projects used in a primary PAF portfolio — they are not commercial products but are intended to show applied skills in UI, layout, and client-side behaviour.

---

## Applications (repositories)

- orenji-fitness-app — Static fitness app with pages for workouts, summaries and settings. Files observed: `index.html`, `treinos.html`, `resumo.html`, `configuracoes.html`, `css/`, `js/`, and `assets/` (logos). Public.
- Orenji-Recipes — Recipe browsing/demo app (static). Files observed: `index.html`, `receita.html`, `pesquisar.html`, `favoritos.html`, `cozinha.html`, plus `css/` and `js/`. Private.
- Orenji-Study — Study tools (notes, calendar, tasks, schedule). Files observed: `index.html`, `dashboard.html`, `notas.html`, `tarefas.html`, `calendario.html`, `horario.html`, plus `css/` and `js/`. Private.
- Orenji-core — Core design assets (CSS and JS used across apps). Files observed: `css/` and `js/`. Private.
- Orenji-Focus-Orenji-Habit — Private repository (appears to contain focus/habit related apps). Access limited; contents were not inspected.
- .github — Organization metadata (this repository). Contains `profile/README.md` (this file will be placed here).

Notes: I inspected each repository's root files and directories to prepare this summary — descriptions above only reflect files actually present in the repositories and do not assume back-end services or user accounts unless explicitly implemented.

---

## Current status

- Overall: In active development (student portfolio). Work focuses on completing UI pages, consolidating a shared design system, and preparing the projects for inclusion in the portfolio.
- Static UI pages: Implemented (HTML/CSS/JS) across repositories as simple single-page flows and multi-page demos.
- Shared core (Orenji-core): Present, containing CSS and JS intended to be shared between apps.
- Back end & persistence: Not present in inspected repos — there is no indication of server-side code or databases in the repositories reviewed.

Completed features (implemented in the repos as of inspection):
- Static pages and navigation for fitness, recipes, and study apps (HTML files found in each repo).
- Visual identity assets (logos) available in `orenji-fitness-app/assets/`.
- Core CSS/JS scaffolding in Orenji-core.

In-development features (what is being worked on or should be considered in-progress):
- Component consolidation and sharing between repositories using Orenji-core.
- Responsive layout and accessibility improvements.
- Preparing consistent README and documentation for each app.

Planned features (suggested / roadmap items; not yet present):
- Client-side data persistence (localStorage or small API) for tasks/notes/favorites.
- Progressive Web App (PWA) support for offline access.
- Continuous integration (linting/build) and automated deployment for portfolio showcasing.

---

## Technologies

Based on repository contents:
- HTML (static pages)
- CSS (plain CSS files in `css/` folders; Orenji-core contains shared styles)
- JavaScript (vanilla JS in `js/` folders)

No frameworks or back-end code were detected in the repositories inspected. If you plan to add frameworks (React/Vue) or Node-based tooling, document that in each repo's README.

---

## Design system

Orenji-core contains the organization’s initial design assets (CSS and JS folders). Current state:
- Core tokens and styles: present as static CSS files — suitable for sharing across static apps.
- Component library: not yet formalized into a component package. Consider extracting variables, utility classes, and a simple documentation page to make reuse easier.

Suggested short-term goals for the design system:
- Add a `README.md` inside Orenji-core that lists available CSS variables, utility classes, and usage examples.
- Create a small example page (e.g., `core/docs.html`) that demonstrates components and color usage.

---

## Repository structure (what I inspected)

- orenji-fitness-app/
  - index.html, inicio.html, treinos.html, resumo.html, configuracoes.html
  - css/ (styles)
  - js/ (scripts)
  - assets/ (logo.png, logo_outline.png)

- Orenji-Recipes/
  - index.html, receita.html, pesquisar.html, favoritos.html, cozinha.html
  - css/
  - js/

- Orenji-Study/
  - index.html, dashboard.html, notas.html, tarefas.html, calendario.html, horario.html
  - css/
  - js/

- Orenji-core/
  - css/
  - js/

- Orenji-Focus-Orenji-Habit/
  - Private repository — not inspected here.

This structure indicates a set of static front-end projects that share a small core repository for styles and scripts.

---

## Academic purpose

These repositories serve as demonstration projects for a student's PAF portfolio. They are intentionally small, focused, and reproducible — ideal for showing HTML/CSS/JavaScript competence, design thinking, and the ability to structure multiple related projects.

When using these repos in academic submissions, please ensure you include proper documentation and credit where third-party assets or code were used.

---

## Roadmap

Short term (next 4–8 weeks):
- Consolidate shared styles into Orenji-core documentation.
- Add README files to each application with setup and run instructions (if any build steps are added).
- Improve responsive styles and keyboard accessibility on interactive pages.

Medium term (3–6 months):
- Add client-side persistence for user data (tasks, notes, favorites).
- Add CI checks (linting) and automated deploy to GitHub Pages for finished apps.
- Add screenshots and demo GIFs into `.github/profile/assets/` and reference them from this profile README.

Long term (optional):
- Turn Orenji-core into a small npm package (if the projects adopt toolchains).
- Add a small back-end API for syncing data (if full-stack features are desired).

---

## Screenshots & assets

Existing image assets discovered:
- orenji-fitness-app/assets/logo.png (used above)
- orenji-fitness-app/assets/logo_outline.png

Recommended location for organization-level images (place them here):
- `.github/profile/assets/` — add screenshots like `fitness-homepage.png`, `study-dashboard.png`, `recipes-list.png`.

Placeholders in this README
- I created references to the `orenji-fitness-app` logo above using the repository's raw URL.
- If you prefer to keep images inside this `.github` repository, add images to `.github/profile/assets/` and update the image links in this file to use relative paths (e.g., `./assets/fitness-homepage.png`).

Alt text: all images used in this README include alt text for accessibility.

---

## License & status

- License: None specified in the inspected repositories. If you want to publish educational or portfolio code publicly, add a license (MIT or similar) to each repository as appropriate.
- Status: Student portfolio work — actively in development. Use for reference and demonstration; not a production-ready project.

---

If you'd like, I can:
- Add example screenshots placeholders to `.github/profile/assets/` (empty `.gitkeep` already included in this commit) and update links.
- Create per-repository README templates summarizing each app and its local run instructions.

Thank you — I inspected the repositories' root files and folders to produce this summary. If you want the README to be stricter or shorter, or to include direct links to each file, tell me which style you prefer.
