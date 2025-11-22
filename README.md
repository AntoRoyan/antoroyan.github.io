# Anto Royan's Blog

A beautiful, minimal Jekyll blog featuring clean typography and responsive design, perfect for writers and developers.

![Blog Preview](https://via.placeholder.com/800x400/191716/FFFFFF?text=Anto+Royan's+Blog)

## ✨ Features

- **Clean, minimal design** focused on typography and readability
- **Responsive layout** that works on all devices
- **Beautiful typography** using the Newsreader font
- **Fast loading** optimized for static site generation
- **SEO friendly** with proper meta tags and structured data
- **Social sharing** integration
- **Reading time** calculation for posts
- **Multiple post layouts** (grid, large images, small images)
- **GitHub Pages compatible**

## 🚀 Quick Start

1. **Fork this repository** or use it as a template
2. **Clone to your local machine**:
   ```bash
   git clone https://github.com/yourusername/blog.git
   cd blog
   ```
3. **Install dependencies**:
   ```bash
   bundle install
   ```
4. **Customize your site** by editing `_config.yml`
5. **Run locally**:
   ```bash
   bundle exec jekyll serve
   ```
6. **Deploy to GitHub Pages** by pushing to your repository

## 📝 Configuration

Edit `_config.yml` to customize your site:

```yaml
title: Your Blog Title
description: Your blog description
author: Your Name
email: your.email@example.com

# Social links
site_config:
  social:
    twitter: yourusername
    linkedin: yourusername  
    github: yourusername
    rss: true
```

## 📖 Creating Posts

Create new posts in the `_posts` directory with this format:

```markdown
---
date: 2024-11-20
title: "Your Post Title"
author: "Your Name"
image: "/assets/images/post-image.jpg"
excerpt: "A brief description of your post"
---

Your post content here...
```

## 🎨 Customization

### Colors and Typography

Customize colors and typography by editing the SCSS variables in `_sass/_theme-variables.scss`:

```scss
// Color Palette
$color-base: #FFFFFF;
$color-contrast: #191716;
$color-contrast-2: #666666;

// Typography
$font-family-body: "Newsreader", ui-serif, "Times New Roman", serif;
```

### Layouts

The theme includes several layout options:

- `default` - Base layout for all pages
- `home` - Homepage with post grid
- `post` - Individual post layout
- `page` - Static page layout

## 📱 Social Features

### Social Sharing

Posts automatically include social sharing buttons. Customize which platforms appear by editing the post layout.

### Social Links

Add your social media profiles in `_config.yml` and they'll appear in the footer.

## 🔧 Development

### File Structure

```
├── _includes/          # Reusable HTML components
├── _layouts/           # Page layouts  
├── _posts/             # Blog posts
├── _sass/              # Stylesheet components
├── assets/             # Images, fonts, CSS
├── _config.yml         # Site configuration
└── Gemfile             # Ruby dependencies
```

### Building Locally

1. Install Ruby and Bundler
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## 🚢 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source: "Deploy from a branch"
4. Choose branch: `main` or `master`
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Other Platforms

This theme works with:
- Netlify
- Vercel  
- GitLab Pages
- Any Jekyll-compatible hosting

## 📜 License

This theme is licensed under the same terms as the original WordPress theme (GPL v2 or later).

## 🙏 Credits

- **Design inspiration**: Minimal typography-focused themes
- **Newsreader font**: [Production Type](https://github.com/productiontype/Newsreader)
- **Built with**: Jekyll for GitHub Pages

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have questions or need help:

1. Check the [Jekyll documentation](https://jekyllrb.com/docs/)
2. Open an issue in this repository
3. Check the [Jekyll documentation](https://jekyllrb.com/docs/)

---

**Enjoy your new Jekyll blog!** 🎉