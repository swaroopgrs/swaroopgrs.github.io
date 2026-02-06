# AI Agent Instructions

Personal website for Swaroop Gadiyaram - Executive Director at JPMorganChase's Machine Learning Center of Excellence.

## Structure

```
index.html          # About page (main)
blog.html           # Blog listing  
posts/              # Blog post files
  reference.html    # Template for new posts
css/styles.css      # All styles
js/script.js        # Theme toggle & nav
```

## Key Files

- **index.html** — About page with bio, expertise section
- **blog.html** — Blog listing (currently empty)
- **posts/reference.html** — Blog post template

## Adding Blog Posts

1. Copy `posts/reference.html` to `posts/new-post.html`
2. Update title, meta, content
3. Add entry to `blog.html`:
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

## Design

- Academicpages-style: left sidebar + main content
- CSS variables in `:root` for theming
- Light/dark toggle via `data-theme` attribute
- Responsive: sidebar stacks on mobile

## Deployment

Push to `main` → GitHub Actions auto-deploys to GitHub Pages.

---

*Theme inspired by [academicpages](https://academicpages.github.io/)*
