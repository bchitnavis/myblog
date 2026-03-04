# Mindful Musings

A personal blog exploring thoughts on life, culture, productivity, investing, and more.

**Live Site:** [View on Netlify](https://app.netlify.com)

## About This Blog

Mindful Musings is a space where I share my perspectives on technology, global affairs, business trends, cultural phenomena, and various aspects of personal growth and investing. Running since 2005, this blog documents my journey through an ever-evolving world.

## Building & Deploying

This blog is built with [Jekyll](https://jekyllrb.com/) and deployed automatically to [Netlify](https://netlify.com).

### Local Development (Optional)

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

### Deployment

The site automatically deploys to Netlify whenever changes are pushed to the `main` branch on GitHub.

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

4. Commit and push to `main` to publish via Netlify.

## Technologies

- **Generator:** Jekyll 4.3.2
- **Theme:** Minimal Mistakes
- **Hosting:** Netlify
- **Repository:** GitHub
