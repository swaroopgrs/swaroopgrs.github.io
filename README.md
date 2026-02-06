# Swaroop Gadiyaram - Personal Portfolio

🌐 **Live Site:** [swaroopgrs.github.io](https://swaroopgrs.github.io)

A modern, premium personal portfolio website built with pure HTML, CSS, and JavaScript.

## ✨ Features

- **Modern Dark Theme** - Premium design with purple/pink gradient accents
- **Animated Background** - Floating gradient orbs and subtle grid pattern
- **Responsive Design** - Works beautifully on desktop, tablet, and mobile
- **Smooth Animations** - Scroll-triggered fade-ins, hover effects, micro-interactions
- **Blog Section** - Ready-to-use blog page for writing articles
- **CI/CD** - Automatic deployment via GitHub Actions

## 📁 Project Structure

```
swaroopgrs.github.io/
├── index.html          # Main portfolio page
├── blog.html           # Blog page
├── styles.css          # All styles
├── script.js           # Navigation and animations
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions CI/CD
└── README.md
```

## 🚀 Deployment

**CI/CD is set up!** Any push to `main` or `master` will automatically deploy.

### First-time Setup

1. Go to your GitHub repository
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment", select **GitHub Actions**

### Deploy Changes

Simply push your changes:
```bash
git add .
git commit -m "Update website"
git push
```

The site will automatically update within 1-2 minutes.

## ✍️ Adding Blog Posts

1. Create a new HTML file (e.g., `blog/my-post.html`)
2. Copy the structure from an existing blog card in `blog.html`
3. Update `blog.html` to link to your new post
4. Push your changes

## 🔗 Profile Links

- **Email**: swaroop.g7@gmail.com
- **GitHub**: [github.com/swaroopgrs](https://github.com/swaroopgrs)
- **LinkedIn**: [linkedin.com/in/swaroopgadiyaram](https://linkedin.com/in/swaroopgadiyaram)
- **Google Scholar**: [scholar.google.com/citations?user=EEFl0e4AAAAJ](https://scholar.google.com/citations?user=EEFl0e4AAAAJ)

## 🛠️ Local Development

Open `index.html` directly in your browser, or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

## 📄 License

MIT License - Feel free to use this as a template for your own portfolio!