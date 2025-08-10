# Creative Web Solutions

Creative Web Solutions is a modern web design and development agency website built with [Astro](https://astro.build/). It features a clean, responsive design, modular components, and pages for services, blog, contact, and more.

## Features

- **Astro Framework**: Fast, modern static site generator.
- **Modular Components**: Reusable UI components for rapid development.
- **Responsive Design**: Mobile-friendly layouts and images.
- **Blog**: Markdown-powered blog posts with custom layout.
- **Contact Form**: Easy-to-customize contact form.
- **Team & Testimonials**: Showcase your team and client feedback.
- **SEO Optimized**: Best practices for search engines.
- **Global Styles**: Centralized CSS for consistent look and feel.

## Project Structure

```
astro.config.mjs
package.json
tsconfig.json
public/           # Static assets
src/
  assets/         # Images for pages and blog
  components/     # UI components (Button, Card, etc.)
  layouts/        # Page layouts
  pages/          # Site pages (index, about, blog, contact, etc.)
  styles/         # Global CSS
```

## Getting Started

1. **Install dependencies**:
   ```bash
   npm install
   ```
2. **Start the development server**:
   ```bash
   npm run dev
   ```
3. **Build for production**:
   ```bash
   npm run build
   ```
4. **Preview production build**:
   ```bash
   npm run preview
   ```

## Customization

- Update images in `src/assets/`.
- Edit content in `src/pages/` and blog posts in Markdown files.
- Modify components in `src/components/` for custom UI.
- Adjust styles in `src/styles/global.css`.
