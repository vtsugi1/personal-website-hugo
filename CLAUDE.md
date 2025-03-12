# Hugo Personal Website Guide

## Commands
- **Build site**: `hugo`
- **Build for production**: `hugo --minify`
- **Start dev server**: `hugo server -D`
- **Create new content**: `hugo new content/posts/my-post.md`
- **Clean cache**: `hugo --cleanDestinationDir`

## Style Guidelines
- **Markdown**: Use standard Markdown with Hugo shortcodes
- **Front Matter**: Use YAML format (---) for front matter
- **Content**: Keep content in /content directory
- **Images**: Store images in /static/images
- **Layout**: Custom layouts go in /layouts
- **CSS**: Custom CSS in /assets/css
- **Config**: Use hugo.toml for site configuration
- **Theme**: PaperMod is the current theme
- **Content Structure**: Follow existing structure in content/ directory
- **Links**: Use relative links to internal content

## Deployment
- Auto-deploys to GitHub Pages on push to master
- Published at: https://vtsugi1.github.io/personal-website-hugo/