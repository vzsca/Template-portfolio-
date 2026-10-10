# Portfolio Template

A flexible, responsive personal portfolio built with **Jekyll** and **GitHub Pages**. It uses a calm terminal-inspired dark theme, plain CSS, and no external JavaScript or font dependencies.

Use it to showcase software projects, creative work, case studies, academic work, professional experience, or personal experiments.

## Quick start

1. Click **Use this template** on GitHub to create your own repository.
2. Edit `_config.yml`: set your site title, GitHub username, repository name, email, and optional social links.
3. Update `index.html` with your name, headline, introduction, and profile.
4. Replace the example project in `_projects/` with your own work.
5. Edit `_data/skills.yml` to match the skills you want to showcase.
6. In GitHub, open **Settings → Pages** and enable deployment from the `main` branch.
7. Check the published site on desktop and mobile.

For a project repository such as `my-portfolio`, set `baseurl: "/my-portfolio"`. For a user site named `YOUR-USERNAME.github.io`, the base URL is usually empty.

## Add a project

1. Copy `_projects/_TEMPLATE.md` to a new Markdown file, such as `2026-01-project-name.md`.
2. Edit its front matter: `title`, `date`, `context`, `type`, `summary`, and `skills`.
3. Use `type: "featured"` for projects you want to highlight, or `type: "other"` for the remaining projects.
4. Describe the goal, your role, tools, process, outcome, and what you learned.
5. Add screenshots to `images/` and provide meaningful alt text.
6. Use skill codes defined in `_data/skills.yml`.

The homepage automatically lists projects and builds the skills matrix from each project's Markdown front matter.

## Project structure

- `index.html` — homepage, profile, projects, skills, and contact
- `_projects/` — Markdown project pages
- `_layouts/default.html` — shared navigation and footer
- `_layouts/project.html` — individual project page layout
- `_data/skills.yml` — editable skills list
- `css/style.css` — theme, components, and responsive layout
- `images/` — screenshots and other images
- `legal-notice.md` — starter legal notice to adapt
- `_config.yml` — Jekyll configuration and contact details

## Customize the design

The color palette is near the top of `css/style.css`, in `:root`. Common variables include `--bg`, `--panel`, `--text`, `--muted`, and `--green`.

The legal notice is a starting point, not legal advice. Adapt it to your location, hosting provider, and the services you actually use.

## License

The template code is released under the MIT License. Content, images, and third-party assets you add may have separate copyright or license terms.
