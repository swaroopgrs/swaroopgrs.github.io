# AI Agent Instructions

Personal website for Swaroop Gadiyaram - Applied AI/ML Director at JPMorganChase.

## Structure

```
index.html      # About page (main)
blog.html       # Blog listing
posts/          # Blog post files
  reference.html  # Template for new posts
css/styles.css  # All styles
js/script.js    # Theme toggle
```

## Key Files

- **index.html**: About page with bio, expertise
- **blog.html**: Blog listing (currently "coming soon")
- **posts/reference.html**: Blog post template - copy this for new posts

## Adding Blog Posts

1. Copy `posts/reference.html` to `posts/new-post.html`
2. Update content, title, meta
3. Add entry to `blog.html` blog-list div:
```html
<article class="blog-item">
    <div class="blog-item-meta">
        <span class="blog-item-date">Date</span>
        <span class="blog-item-category">Category</span>
    </div>
    <h3 class="blog-item-title">
        <a href="posts/new-post.html">Title</a>
    </h3>
    <p class="blog-item-excerpt">Description</p>
</article>
```

## Design System

- CSS variables in `:root` for colors/spacing
- Light/dark theme via `data-theme` attribute
- Academicpages-style layout: sidebar + main content
- Responsive: sidebar stacks on mobile

## Deployment

Push to `main` → GitHub Actions auto-deploys to GitHub Pages.

---

*Theme inspired by [academicpages](https://academicpages.github.io/)*
