# OpenHealth Official Website

This is the official website for **OpenHealth**, an AI-powered health monitoring and management iOS application. The site is built with **Next.js** and [Nextra](https://nextra.vercel.app/), allowing content to be written in Markdown for easy maintenance.

## Features

- **AI Health Monitoring**: Real-time tracking and intelligent insights.
- **Digital Twin Creation**: LLM-powered personalized digital twins.
- **Privacy-Preserving**: Local data processing on iOS devices.
- **Blog Integration**: Share updates, health tips, and app news via the integrated blog.
- **RSS Feed**: Automatically generated RSS feed for posts.
- **Responsive Design**: Beautiful, mobile-friendly theme.

## Configuration

1. Update site details in `theme.config.js`.
2. Modify RSS feed settings in `scripts/gen-rss.js`.
3. Customize meta tags in `pages/_document.js`.
4. Add or edit blog posts in `pages/posts/*.md`.

## Deploy

Deploy using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/openhealth-dev/openhealth-dev.github.io&project-name=openhealth-dev-github-io&repository-name=openhealth-dev.github.io)

