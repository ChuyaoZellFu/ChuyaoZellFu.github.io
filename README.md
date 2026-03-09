# Chuyao Fu's Personal Website

A clean, academic personal website for PhD applications in Robot Learning.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Clean Academic Style**: Professional and easy to read
- **Key Sections**:
  - Home: Introduction and research highlights
  - Publications: Paper listings with filtering
  - Projects: Research and course projects
  - CV: Download link

## Local Development

```bash
# Install Jekyll (first time only)
gem install jekyll bundler

# Serve locally
cd chuyaofu-website
bundle exec jekyll serve

# Open browser to http://localhost:4000
```

## Deployment

This site is designed to be deployed on **GitHub Pages**:

1. Create a repository named `ChuyaoZellFu.github.io`
2. Push these files to the repository
3. Enable GitHub Pages in Settings
4. Site will be live at https://ChuyaoZellFu.github.io

## Customization

### To customize content:
- Edit `_pages/index.md` for homepage
- Edit `_pages/publications.md` for papers
- Edit `_pages/projects.md` for projects
- Add your photo to `assets/images/profile.jpg`
- Add your CV to `assets/cv.pdf`

### To change colors:
- Edit CSS variables in `assets/css/style.css`

## Structure

```
chuyaofu-website/
├── _config.yml          # Site configuration
├── _layouts/
│   └── default.html     # Main layout template
├── _pages/
│   ├── index.md         # Homepage
│   ├── publications.md  # Publications page
│   └── projects.md      # Projects page
├── assets/
│   ├── css/
│   │   └── style.css    # Stylesheet
│   ├── images/          # Images
│   └── cv.pdf           # Your CV
└── README.md
```

## Credits

Built with Jekyll and hosted on GitHub Pages.
