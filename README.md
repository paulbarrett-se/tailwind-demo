# Tailwind CSS Flexbox Reference Guide

A quick-reference guide mapping CSS Flexbox properties to their Tailwind CSS utility class equivalents. Built for presentations, onboarding, and everyday development.

## What This Project Does

This project provides a single-page reference that:

- **Maps CSS to Tailwind** — Side-by-side comparisons showing vanilla CSS flexbox properties and their Tailwind equivalents
- **Covers all flexbox properties** — Both parent (container) and child (item) properties
- **Serves as a quick lookup** — Sticky navigation and a summary table for fast reference during development

## What is Tailwind CSS?

[Tailwind CSS](https://tailwindcss.com) is a **utility-first CSS framework** that provides low-level utility classes to build custom designs directly in your HTML. Instead of writing custom CSS or using pre-built components, you compose styles using small, single-purpose classes like `flex`, `justify-center`, `p-4`, and `text-lg`.

```html
<!-- Traditional CSS approach -->
<div class="card">...</div>

<!-- Tailwind approach -->
<div class="bg-white rounded-lg shadow-md p-6">...</div>
```

## Why Tailwind is Useful

### For Individual Developers

- **Faster development** — No context-switching between HTML and CSS files
- **No naming fatigue** — Stop inventing class names like `.card-wrapper-inner-container`
- **Responsive by default** — Built-in responsive prefixes (`sm:`, `md:`, `lg:`) make mobile-first design simple
- **Consistent spacing and sizing** — A constrained design system prevents arbitrary values

### For Teams

- **Shared vocabulary** — Everyone uses the same utility classes, making code reviews easier
- **Reduced CSS bloat** — No duplicate styles scattered across files; utilities are reused
- **Predictable styling** — Reading `class="flex items-center gap-4"` tells you exactly what an element does
- **Easier onboarding** — New team members learn one system instead of navigating custom CSS architectures
- **Design system enforcement** — Tailwind's default theme (or your custom config) ensures consistency across the codebase
- **No CSS conflicts** — Utility classes are scoped and don't accidentally override each other

### The Result

Teams using Tailwind often report:
- Faster feature development
- Smaller CSS bundle sizes (especially with PurgeCSS/JIT)
- More consistent UIs across the application
- Less time spent debugging CSS specificity issues

## Useful Links

| Resource | Description |
|----------|-------------|
| [Tailwind CSS Official Site](https://tailwindcss.com) | Documentation, installation guides, and examples |
| [Tailwind CSS Documentation](https://tailwindcss.com/docs) | Complete reference for all utility classes |
| [Tailwind Play](https://play.tailwindcss.com) | Online playground to experiment with Tailwind |
| [Tailwind UI](https://tailwindui.com) | Official premium component library |
| [Headless UI](https://headlessui.com) | Unstyled, accessible UI components for Tailwind |
| [Heroicons](https://heroicons.com) | Beautiful hand-crafted SVG icons by the Tailwind team |
| [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) | The original flexbox reference this project is based on |

## Running Locally

Simply open `index.html` in your browser. The project uses the Tailwind CDN, so no build step is required.

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

## License

MIT
