---
title: How to Create Blog Posts
date: 2026-06-05
categories: [tutorial]
tags: [jekyll, markdown, github-pages]
---

# How to Create Blog Posts

Creating blog posts for this Jekyll-powered blog is simple and straightforward. Let me walk you through the process.

## Step 1: Create a New File

Create a new markdown file in the `_posts` directory with the naming convention:

```
YYYY-MM-DD-title-of-your-post.md
```

For example:
- `2026-06-05-my-first-post.md`
- `2026-06-06-github-tips.md`
- `2026-06-07-web-development.md`

## Step 2: Add Front Matter

Start your file with YAML front matter enclosed in triple dashes:

```yaml
---
title: My Amazing Blog Post
date: 2026-06-05
author: Your Name
categories: [technology, tutorial]
tags: [github, jekyll, blogging]
---
```

### Front Matter Fields

- **title**: The title of your blog post (required)
- **date**: Publication date in YYYY-MM-DD format (required)
- **author**: Author name (optional)
- **categories**: List of categories for organization (optional)
- **tags**: Tags for better discoverability (optional)

## Step 3: Write Your Content

After the front matter, write your blog post content in Markdown:

```markdown
# Main Heading

This is a paragraph with **bold** and *italic* text.

## Subheading

Here's a list:
- Item 1
- Item 2
- Item 3

### Code Example

```javascript
function hello() {
  console.log('Hello, World!');
}
```

[Link to example](https://example.com)
```

## Step 4: Commit and Push

Add your post to Git and push to GitHub:

```bash
git add _posts/2026-06-05-my-new-post.md
git commit -m "Add new blog post: My Amazing Post"
git push origin main
```

## Step 5: GitHub Pages Builds Your Site

GitHub Pages will automatically:

1. Detect your new post
2. Build the site with Jekyll
3. Deploy it to your site

Your post will be live in a few seconds!

## Markdown Formatting Guide

### Headings

```markdown
# H1 Heading
## H2 Heading
### H3 Heading
```

### Text Formatting

```markdown
**bold text**
*italic text*
***bold and italic***
~~strikethrough~~
```

### Lists

```markdown
- Unordered item 1
- Unordered item 2

1. Ordered item 1
2. Ordered item 2
```

### Code Blocks

````markdown
```javascript
const greeting = 'Hello, World!';
console.log(greeting);
```
````

### Blockquotes

```markdown
> This is a blockquote.
> It can span multiple lines.
```

### Links and Images

```markdown
[Link text](https://example.com)
![Image alt text](https://example.com/image.jpg)
```

## Tips for Great Blog Posts

1. **Use Clear Headings**: Help readers scan your post
2. **Break Up Text**: Use short paragraphs and lists
3. **Add Code Examples**: Make tutorials practical
4. **Use Categories and Tags**: Help with organization and SEO
5. **Proofread**: Check for typos and grammar
6. **Add Images**: Break up text with visuals
7. **Write Naturally**: Write as if you're explaining to a friend

## Viewing Locally

Before pushing to GitHub, you can preview your site locally:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then visit `http://localhost:4000/ideas` in your browser.

## Common Issues

### Post Not Showing Up?

- Check the file name format: `YYYY-MM-DD-title.md`
- Ensure front matter is enclosed in `---`
- Check for YAML syntax errors
- Wait a few seconds for GitHub Pages to build

### Dates are Off?

- Ensure dates in front matter are in `YYYY-MM-DD` format
- The date in the filename and front matter should match

## Resources

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Help](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

Now you're ready to start blogging! Happy writing! ✍️
