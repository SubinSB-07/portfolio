# Subin S B | Personal Portfolio

A dark, minimal, animation-driven portfolio website built as a single HTML file. It showcases my skills, projects and contact details, with smooth scrolling, a custom cursor and scroll-triggered animations.

**Live site:** subinsb-portfolio.netlify.app


---

## About

I'm Subin S B, a B.Tech CSE (AI & ML) student interested in full-stack development, Generative AI and workflow automation. This portfolio is a showcase of my skills and the way I like to build: clean interfaces on solid foundations.

## Features

- Near-black editorial design with a single cyan accent color (changeable from one CSS variable)
- Animated intro loader and hero headline reveal
- Custom cursor with a trailing ring that reacts to links, buttons and project cards
- Smooth scrolling with Lenis, synced with GSAP ScrollTrigger
- Scroll-reveal animations, magnetic buttons and 3D tilt effect on project cards
- Scroll progress bar and active section highlighting in the navbar
- Fully responsive layout with a mobile navigation menu
- Contact form powered by Formspree (no backend required)
- Accessibility support: skip link, keyboard navigation, focus states, `prefers-reduced-motion` support
- Single file, no build step

## Tech Stack

| Area | Tools |
| --- | --- |
| Markup and styling | HTML5, CSS3, Tailwind CSS (CDN) |
| Animation | GSAP, ScrollTrigger, Lenis |
| Forms | Formspree |
| Hosting | Netlify |
| Version control | Git and GitHub |

## Sections

1. **Home:** animated hero with intro and call-to-action buttons
2. **About:** short bio and focus areas
3. **Skills:** frontend, backend, databases, languages, AI and automation, DSA
4. **Projects:** project cards (currently sample concepts, to be replaced with real work)
5. **Contact:** email, social links and contact form

## Run Locally

No installation is needed.

```bash
git clone https://github.com/SubinSB-07/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

Then open `index.html` in your browser. An internet connection is needed to load the fonts and CDN libraries. For auto-refresh while editing, use the VS Code **Live Server** extension.

## Customize

- **Accent color:** change `--accent` in the `:root` block at the top of the CSS
- **Content:** search `index.html` for `EDIT` comments
- **Contact form:** replace `YOUR_FORM_ID` in the form `action` with your Formspree form ID
- **Resume:** add your PDF to the project folder and set `resumeUrl` in the `CONFIG` object near the bottom of the file

## Deployment

The site is deployed on Netlify as a static site with no build command. Any change pushed to the `main` branch can be redeployed automatically when the repository is connected to Netlify.

## Roadmap

- [ ] Add real projects with live demos and GitHub links
- [ ] Add a dark/light theme toggle
- [ ] Add an AI assistant that answers questions about my work
- [ ] Show live GitHub and coding stats
- [ ] Add a custom domain

## Contact

- Email: sbsubin7127@gmail.com
- GitHub: [@SubinSB-07](https://github.com/SubinSB-07)
- LinkedIn: [Subin S B](https://www.linkedin.com/in/subin-sb-00b39536b/)

---

Built with curiosity.
