# Mindful Musings

A personal blog exploring thoughts on life, culture, productivity, investing, and more.

**Live Site:** [View on GitHub Pages](https://bchitnavis.github.io/myblog)

## About This Blog

Mindful Musings is a space where I share my perspectives on technology, global affairs, business trends, cultural phenomena, and various aspects of personal growth and investing. Running since 2005, this blog documents my journey through an ever-evolving world.

## Building & Deploying

This blog is built with [Jekyll](https://jekyllrb.com/) and deployed automatically to [GitHub Pages](https://pages.github.com/).

### Local Development (Optional)

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

### Deployment

The site automatically deploys to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

> **Legacy note:** A `netlify.toml` is still present in the repository for optional Netlify deploys, but GitHub Pages is now the canonical hosting target.

## Adding a New Post

Use the template file at `templates/post-template.md`.

1. Copy it into `_posts/` with a Jekyll filename:

	```bash
	cp templates/post-template.md _posts/YYYY-MM-DD-your-title.md
	```

2. Edit front matter values:
	- `title`
	- `date`
	- `categories`
	- `tags`

3. Write your content below the front matter.

4. Commit and push to `main` to publish via GitHub Pages.

## Technologies

- **Generator:** Jekyll 4.3.2
- **Theme:** Minimal Mistakes
- **Hosting:** GitHub Pages
- **Repository:** GitHub
