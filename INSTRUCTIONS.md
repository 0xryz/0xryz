# Instructions for Creating New Articles

## Creating a New Writeup

1. Create a new markdown file in the `_writeups/` folder
2. Name the file: `YYYY-MM-DD-your-title-slug.md`
   - Example: `2024-12-28-sql-injection-vulnerability.md`
3. Use the following template:

```markdown
---
title: "Your Writeup Title"
collection: writeups
permalink: /writeups/YYYY-MM-DD-your-title-slug/
date: YYYY-MM-DD
excerpt: "A brief description of the vulnerability (appears in listings)"
header:
  teaser: /images/your-image.png
---

Your writeup content here. Use markdown formatting.

## Section Title

Content goes here.

### Code Example

```python
# Your code here
```

![Image Description](/images/your-image.png)
```

## Creating a New Story

1. Create a new markdown file in the `_stories/` folder
2. Name the file: `YYYY-MM-DD-your-title-slug.md`
   - Example: `2024-12-28-my-first-bug-bounty.md`
3. Use the following template:

```markdown
---
title: "Your Story Title"
collection: stories
permalink: /stories/YYYY-MM-DD-your-title-slug/
date: YYYY-MM-DD
excerpt: "A brief description of your story (appears in listings)"
header:
  teaser: /images/your-image.png
---

Your story content here. Use markdown formatting.

## Section Title

Content goes here.

![Image Description](/images/your-image.png)
```

## Important Notes

- **Date Format**: Always use `YYYY-MM-DD` format (e.g., `2024-12-28`)
- **Collection**: Must be either `writeups` or `stories` (don't change this)
- **Permalink**: Should match your filename (without the `.md` extension)
- **Images**: Place images in the `images/` folder and reference them with `/images/filename.png`
- **Markdown**: You can use all standard markdown features:
  - Headers (`#`, `##`, `###`)
  - Code blocks (with syntax highlighting)
  - Lists (ordered and unordered)
  - Links, images, bold, italic, etc.

## File Structure

```
_writeups/
  └── YYYY-MM-DD-title.md

_stories/
  └── YYYY-MM-DD-title.md

images/
  └── your-image.png
```

## After Creating

1. Save your file
2. Commit and push to GitHub:
   ```bash
   git add _writeups/YYYY-MM-DD-your-file.md
   git commit -m "Add new writeup: Your Title"
   git push origin master
   ```
3. Your article will appear automatically on the Writeups or Stories page

## Tips

- Keep titles descriptive but concise
- Use the excerpt to give readers a preview
- Add images to make your content more engaging
- Use code blocks for technical content
- Structure your content with clear sections

