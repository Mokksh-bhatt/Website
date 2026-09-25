# Mokksh Bhatt — Portfolio Website

A single-page personal portfolio site with a dark theme, showcasing my background, skills, and projects.

## Sections

- **Home** — introduction and a call-to-action linking to the projects section
- **About** — profile photo, short bio, and a list of skills
- **Projects** — cards for featured projects, each with a screenshot, tech stack, and live demo link
- **Contact** — email link for getting in touch
- **Footer** — links to GitHub and LinkedIn

## Featured Projects

| Project | Description | Stack | Live Demo |
| --- | --- | --- | --- |
| AI Personal Trainer | AI-powered trainer that gives personalized workout advice | React, Tailwind, Firebase | [gemini-guide-cc9e0.web.app](https://gemini-guide-cc9e0.web.app/) |
| Design Critique | SaaS platform providing UI/UX critiques and conversion-focused feedback | Next.js, Tailwind CSS, JavaScript | [designcritique.web.app](http://designcritique.web.app/) |
| Nope-Pad | Note-taking app with the convenience of a notepad and features of a text editor | JavaScript, SCSS, Local Storage | [nope-pad.web.app](https://nope-pad.web.app/) |

## Tech

The site is plain HTML, CSS, and a small amount of vanilla JavaScript (for the mobile menu), all contained in `index.html`. There are no dependencies or build steps; the only external resource is the [Inter](https://fonts.google.com/specimen/Inter) font from Google Fonts.

## Project Structure

```
.
├── index.html   # The entire site: markup, styles, and script
├── gemini.png   # Screenshot for AI Personal Trainer
├── image.png    # Screenshot for Design Critique
├── nope.png     # Screenshot for Nope-Pad
└── LICENSE
```

## Running Locally

Open `index.html` directly in a browser, or serve the folder with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

Because the site is fully static, it can be hosted on any static hosting service (GitHub Pages, Firebase Hosting, Netlify, etc.) by publishing the repository root.

## Contact

- Email: [mokkshbhatt@gmail.com](mailto:mokkshbhatt@gmail.com)
- GitHub: [@Mokksh-bhatt](https://github.com/Mokksh-bhatt)
- LinkedIn: [Mokksh Bhatt](https://www.linkedin.com/in/mokksh-bhatt-503621363/)

## License

This project is licensed under the [MIT License](LICENSE).
