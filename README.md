# Kittinan Petsri — Personal Academic Website

[![Built with HTML](https://img.shields.io/badge/Built_with-HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![Styled with CSS](https://img.shields.io/badge/Styled_with-CSS3-1572B6?style=flat&logo=css3&logoColor=white)](#)
[![Hosted on GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-181717?style=flat&logo=github&logoColor=white)](#)

Personal academic portfolio website for **Kittinan Petsri** — researcher in Deep Learning, Smart Education Systems, and Industrial Automation at the Faculty of Technical Education, KMUTNB.

> A single-page, responsive site showcasing publications, projects, career timeline, skills, and awards.

---

## Features

- Responsive design (desktop, tablet, mobile)
- Dark mode toggle with system-preference detection
- Animated hero with gradient blobs and rotating profile ring
- Career timeline with reveal-on-scroll animations
- Skill bars with count-up animation
- Sections: About, Timeline, Research, Publications, Projects, Skills, Awards, Contact
- No build step — pure HTML, CSS, and vanilla JavaScript

## Stack

- HTML5
- CSS3 (custom properties, grid, flex)
- Vanilla JavaScript (IntersectionObserver for scroll animations)
- Google Fonts: Plus Jakarta Sans, JetBrains Mono, Sarabun

## Local Development

Just open `index.html` in any modern browser — no server or build step required.

```bash
# Optional: serve with Python for live preview
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment (GitHub Pages)

This repository is configured for deployment via GitHub Pages.

1. Fork or clone this repo and rename it to `<your-username>.github.io`
2. Push to `main` branch
3. Go to **Settings → Pages**, select **Deploy from branch** → `main` / `(root)`
4. Visit `https://<your-username>.github.io`

See `GitHub_Pages_Guide.docx` for the detailed step-by-step walkthrough (in Thai).

## File Structure

```
.
├── index.html           # Main page
├── style.css            # All styles
├── img/                 # Profile photo and assets
│   └── kittinan.jpg     # (Replace with your photo)
├── README.md            # This file
├── LICENSE              # MIT License
└── .gitignore           # Files to exclude from git
```

## Customization

- **Colors** — edit CSS variables in `:root` of `style.css` (`--cyan`, `--violet`, `--amber`, etc.)
- **Content** — edit text inside `index.html`
- **Profile photo** — drop your photo into `img/` and update the `<img>` tag in the hero section

## Contact

- Email: kittinan.p@fte.kmutnb.ac.th
- Office: Faculty of Technical Education, KMUTNB
- [Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=th&user=2wEVpBUAAAAJ) · [ORCID](https://orcid.org/0009-0004-7938-1447) · [Scopus](https://www.scopus.com/authid/detail.uri?authorId=60021685900)

## License

MIT — see [LICENSE](LICENSE) for details. Feel free to fork and adapt for your own academic site.
