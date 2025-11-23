# bbc

A personal notebook and blogging site powered by Hugo with the Anubis theme. This project serves as a platform for capturing ideas, reflections, and personal articles in a simple, minimalist style.

---

## Features

- Minimalist and responsive design using the Anubis Hugo theme
- Dark mode support with automatic and manual toggling
- Pagination and archive support for posts
- Taxonomies for categories, tags, and series
- Social icons and RSS feeds
- Multiple comment system integrations including Disqus, Isso, and Utteranc.es
- Google Analytics integration
- Custom CSS and JS support
- Multilingual support with translations
- Copy code button for code blocks
- Related posts display (Read Next section)
- Support for math typesetting using KaTeX
- Hidden posts feature (accessible only by link)
- Webmentions and SEO optimizations

## Tech Stack

- [Hugo](https://gohugo.io/) static site generator (requires extended version)
- Anubis Hugo theme (https://github.com/mitrichius/hugo-theme-anubis)
- HTML, CSS, JavaScript
- Google Analytics for tracking
- Optional comment systems: Disqus, Isso, Utteranc.es

## Getting Started

### Prerequisites

- Install [Hugo extended version](https://gohugo.io/getting-started/installing/)
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/bbc.git
cd bbc
```

Add the Anubis theme as a git submodule:

```bash
git submodule add https://github.com/mitrichius/hugo-theme-anubis.git themes/anubis
```

### Running the site locally

```bash
hugo server -D
```

Visit `http://localhost:1313` in your browser to see the site.

### Building for production

```bash
hugo
```

The generated site will be in the `public/` directory.

## Project Structure

```
bbc/
├── archetypes/          # Content archetypes for new posts
├── assets/              # Asset files like CSS and JS
├── config.yaml          # Site configuration file
├── content/             # Markdown content files (posts, pages)
├── layouts/             # Custom Hugo layouts
├── public/              # Generated site output
├── resources/           # Hugo resources
├── static/              # Static files served as-is
└── themes/              # Hugo themes (Anubis theme here)
```

- `config.yaml` contains site-wide settings including base URL, menus, taxonomies, and parameters.
- `content/` holds posts and pages, organized by categories and tags.
- `themes/anubis/` contains the theme files with support for dark mode, pagination, and more.

## Future Work / Roadmap

- Add a detailed site description and improve metadata for SEO
- Expand multilingual support beyond existing translations
- Integrate additional social media sharing options
- Implement automated deployment workflows
- Enhance accessibility features
- Add more custom shortcodes for rich content embedding

---

*Note: This README assumes the project is a personal Hugo-based blog site using the Anubis theme, inferred from the configuration and theme files.*