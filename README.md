# My Ideas Blog

Welcome to my personal blog built with GitHub Pages and Jekyll!

## About

This is a space where I share my ideas, thoughts, and projects. Feel free to explore and connect with me.

## Blog Posts

You can find all my blog posts in the [Blog](./blog) section. New posts are published regularly.

## Getting Started

### Running Locally

To run this blog locally:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then open [http://localhost:4000/ideas](http://localhost:4000/ideas) in your browser.

### Adding New Posts

Create a new markdown file in the `_posts` folder with the naming convention:
`YYYY-MM-DD-title.md`

Example:
```markdown
---
title: My First Post
date: 2026-06-05
categories: [tutorial]
tags: [github, pages]
---

Your blog content here...
```

## Repository Structure

```
ideas/
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML layouts
│   ├── default.html
│   ├── post.html
│   └── home.html
├── _posts/              # Blog posts
│   └── YYYY-MM-DD-title.md
├── _includes/           # Reusable components
├── assets/              # CSS, JS, images
│   └── style.css
├── blog/                # Blog index page
│   └── index.html
├── index.md             # Homepage
└── README.md            # This file
```

## License

MIT License - Feel free to use this template for your own blog!
