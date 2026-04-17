# Mohamed Aziz Soudani - Portfolio

A personal portfolio website showcasing my work as a second-year Software Engineering student at Ted University.

## About

This is my personal portfolio built with pure HTML/CSS/JS, deployed on GitHub Pages.

### Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **JavaScript** - Typing animation & mobile menu
- **GitHub Pages** - CI/CD deployment via GitHub Actions

## Features

- 🌙 Dark theme with neon accents
- ⌨️ Typing animation on hero section
- 📱 Fully responsive (mobile-friendly)
- 🚀 Automatic deployment via GitHub Actions

## Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, title, bio, CTA buttons |
| **About** | Who I am, education, interests |
| **Skills** | Programming, Systems, Tools |
| **Projects** | Shell, Packet Analyzer, Memory Allocator, RE Toolkit |
| **Contact** | Social links, static contact form |

## Deployment

The site automatically deploys to GitHub Pages on every push to `main`.

```bash
# Make changes
git add .
git commit -m "Update portfolio"
git push origin main
```

**Live URL:** https://erlk0nig.github.io/portfolio

## Local Development

```bash
# Clone the repo
git clone https://github.com/Erlk0nig/portfolio.git
cd portfolio

# Open in browser
# Simply open index.html in your browser
# Or use a local server:
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

### Update Personal Info

Edit `index.html` to change:
- Name, bio, title
- Education details
- Skills and percentages
- Project descriptions

### Update Social Links

Find and replace the `href="#"` in the social-links section with your actual URLs.

## License

MIT License - Feel free to use this as a template for your own portfolio!