---
slug: github-bbc-writing-overview
id: github-bbc-writing-overview
title: 'BBC: My Personal Notebook and Blogging Platform'
repo: justin-napolitano/bbc
githubUrl: https://github.com/justin-napolitano/bbc
generatedAt: '2025-11-24T17:06:43.756Z'
source: github-auto
summary: >-
  I built BBC because I wanted a straightforward way to jot down my thoughts and
  share them with the world. It's a personal notebook and blogging platform that
  leverages Hugo and the Anubis theme. The goal? A minimalist and responsive
  design that lets me capture ideas and reflections without the clutter.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: writing
entryLayout: writing
showInProjects: false
showInNotes: false
showInWriting: true
showInLogs: false
---

I built BBC because I wanted a straightforward way to jot down my thoughts and share them with the world. It's a personal notebook and blogging platform that leverages Hugo and the Anubis theme. The goal? A minimalist and responsive design that lets me capture ideas and reflections without the clutter. 

## Why BBC Exists

In a world of complex blogging platforms, I craved simplicity. I needed something I could customize and control without drowning in options. BBC is my solution. It’s designed for:

- Capturing ideas quickly
- Writing personal articles
- Keeping the interface out of my way

With BBC, I can focus on content instead of wrestling with the software.

## Key Design Decisions

I aimed for a clean layout and intuitive navigation. Here’s a breakdown of the choices I made:

- **Minimalist Design**: I chose the Anubis theme for its sleek appearance and mobile responsiveness.
- **Dark Mode**: I included a dark mode toggle because, let’s be honest, it's 2023 and we need to protect our eyes. 
- **Taxonomies**: Implementing categories, tags, and series helps keep my thoughts organized. Plus, readers can easily find related content.
- **Comment System Flexibility**: I wanted to support multiple comment systems—think Disqus, Isso, and Utteranc.es—so users can connect in ways they prefer. 

Each decision was aimed at creating a seamless experience for both me as the writer and my audience.

## Stack and Tools

Let’s get technical for a moment. Here’s what I’m using behind the scenes:

- **Hugo**: A static site generator that’s fast and reliable. I opted for the extended version for added functionality.
- **Anubis Theme**: This theme is not just pretty; it’s purpose-built for responsiveness and ease of use.
- **HTML/CSS/JS**: Standard web tech stack, making customizations straightforward.
- **Google Analytics**: For tracking my blog’s performance without headaches.
  
### Future Features

I’ve got a vision for where I want to take BBC. Future enhancements include:

- Better multilingual support and translations.
- More comment system integrations for flexibility.
- Improvements on SEO and webmentions.
- Additional theme customizations for personalization.
- Automation of the deployment process—gotta love CI/CD.
- Expanding documentation to ease onboarding for anyone interested.

## Getting Started with BBC

If you’re curious to try it out, here’s how to set things up:

### Prerequisites

1. Install the [extended version of Hugo](https://gohugo.io/getting-started/installing/).
2. Make sure you have Git installed.

### Cloning the Repo

Start by cloning BBC to your machine:

```bash
git clone https://github.com/justin-napolitano/bbc.git
cd bbc
```

Next, add the Anubis theme as a submodule:

```bash
git submodule add https://github.com/mitrichius/hugo-theme-anubis.git themes/anubis
```

### Running Locally

To kick the tires, run:

```bash
hugo server -D
```

Then open your browser and head over to `http://localhost:1313`. You’ll see BBC in action.

### Building for Production

When you’re ready to deploy, run:

```bash
hugo
```

Your static site will pop up in the `public/` directory, ready for the world.

## Project Structure

For those who appreciate a good file structure, here’s how BBC is organized:

```
bbc/
├── archetypes/          # Content templates for new posts
├── assets/              # Styles and scripts
├── config.yaml          # Site config file
├── content/             # Where the posts live
├── layouts/             # Templates for layout
├── public/              # Where the static output lives
├── resources/           # Hugo resource files
├── static/              # Files served as-is
├── themes/              # Hugo themes (Anubis as a submodule)
├── README.md            # The documentation
```

## Final Thoughts

Building BBC has been a journey. I appreciate the simplicity and power of Hugo and the Anubis theme. It’s not just a blogging tool; it’s a reflection of how I want to share my thoughts.

I’m always looking to improve. If you’re interested in following the project or catching updates, you can find me on Mastodon, Bluesky, and Twitter/X. Let’s connect and share ideas!

In wrapping up, I hope you find BBC as enjoyable to use as I do. Dive in, write something meaningful, and make it your own!
