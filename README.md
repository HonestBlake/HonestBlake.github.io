# Blake Worthington — Engineering Portfolio

A personal portfolio for Blake Worthington, a Computer Engineering student and Software & Security Engineering graduate student at Texas Tech University. The site highlights selected software and embedded projects, professional experience, education, technical skills, and a downloadable résumé.

## Technologies

- Semantic HTML5
- Modern CSS3
- Responsive layout and accessible navigation
- GitHub Pages

## View the portfolio

Visit the deployed site at [www.honestblake.com](https://www.honestblake.com/).

To view it locally, clone this repository and open `index.html` in a browser. You can also serve the repository directory with any static file server; no installation or build command is required. For example:

```shell
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Repository structure

- `index.html` — introduction and primary navigation
- `about.html` — background and contact information
- `education.html` — degree programs and academic direction
- `projects.html` — selected-project index
- `projects/` — individual project case studies
- `experience.html` — professional and research experience
- `skills.html` — technical skills
- `custom.css` — shared visual system, components, and responsive layouts
- `assets/logos/` — locally hosted organization marks used for identification
- `profile_pic.png` — profile portrait
- `resume.pdf` — downloadable résumé
- `CNAME` — custom-domain configuration for GitHub Pages

## Deployment

This repository is the source for the GitHub Pages site at `https://www.honestblake.com/`. Changes become public after they are merged into the publishing branch and GitHub Pages finishes deployment. Every page is static HTML and shares a single stylesheet, so the site works directly with GitHub Pages without a separate build process.
