---
slug: "github-bbc"
title: "bbc"
repo: "justin-napolitano/bbc"
githubUrl: "https://github.com/justin-napolitano/bbc"
generatedAt: "2025-11-23T08:16:49.381245Z"
source: "github-auto"
---


# My Journey Building "bbc": A Personal Notebook Powered by Hugo

Hey there! I wanted to share some thoughts and insights about my project "bbc", which is essentially my personal notebook and blogging platform. If you've ever felt the need for a place to just jot down your ideas, reflections, or articles without the fuss of complicated CMSs, this might resonate with you.

## Motivation

For a long time, I was creating professional blogs and websites aimed at showcasing my talents and portfolio. While those projects served their purpose, I realized I was taking myself a bit too seriously. I wanted a space where I could freely write whatever was on my mind — no pressure, no polished marketing speak, just raw thoughts and ideas. That's how "bbc" came to be.

## The Problem It Solves

Many blogging platforms are either too complex or too rigid. They often push you to maintain a certain style or format, which can be stifling when you're just trying to capture fleeting thoughts or personal reflections. "bbc" solves this by being a simple, fast, and flexible static site built with Hugo, allowing me to write in Markdown, organize content with categories, tags, and series, and publish without the overhead of databases or server-side code.

## How It's Built

I chose [Hugo](https://gohugo.io/) as the static site generator because of its speed, flexibility, and excellent support for modern web features. The project uses the Anubis theme, which is minimalist and supports dark mode, pagination, and various comment systems like Disqus and Isso.

The configuration (`config.yaml`) is tailored to my needs — setting up menus for Feed, Archive, Tags, Categories, and Series. I also configured Google Analytics for tracking and enabled features like copy-to-clipboard buttons for code snippets.

Content-wise, I write posts in Markdown under the `content/posts` directory, categorizing them for easy navigation. The site supports math typesetting with KaTeX, which is great for any technical notes I want to include.

## Interesting Implementation Details

- **Comment Systems:** I have support for multiple comment platforms, including Disqus, Isso, and Utteranc.es. This flexibility allows me to choose or switch based on my preferences or privacy considerations.

- **Copy Code Button:** The site includes a handy copy button on code blocks, implemented in JavaScript, making it easier for readers to copy code snippets.

- **Hidden Posts:** Some posts can be marked as hidden, making them accessible only by direct link. This is perfect for sharing drafts or private notes.

- **Multilingual Support:** The Anubis theme includes translations for several languages, which is a nice-to-have for potential future expansion.

- **Math Support:** By integrating KaTeX, I can write beautiful mathematical notation directly in my posts.

## Why this project matters for my career

This project is more than just a blog; it's a reflection of my journey as a developer and writer. Building "bbc" has helped me deepen my understanding of static site generation, theming with Hugo, and modern web development best practices. It also serves as a living portfolio of my thoughts and skills, which I can share with peers, employers, or collaborators.

Moreover, maintaining this project keeps me engaged with the open-source ecosystem and sharpens my ability to quickly adapt and customize tools to fit my unique needs.

Thanks for reading! If you’re interested in static sites or personal blogging, I hope this inspires you to create your own space to write and share.

---

*Justin Napolitano*