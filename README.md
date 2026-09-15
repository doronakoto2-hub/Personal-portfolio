# Personal Portfolio Website

A fast, lightweight, multi-page personal portfolio built with clean, modern HTML5 and pure CSS.

## Vercel Deployment Instructions

This repository is optimized for deployment on [Vercel](https://vercel.com).

### Automatic Deployment (Recommended)
1. Push your repository to GitHub, GitLab, or Bitbucket.
2. In Vercel, click **Add New...** > **Project** and import this repository.
3. Vercel automatically detects the build settings:
   - **Framework Preset**: `Vite` (or `Other`)
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: `npm install`
4. Click **Deploy**.

### Project Structure & Pages
- `index.html` - Homepage (Hero, About Me, Interests, Goals)
- `projects.html` - 10-card project showcase
- `skills.html` - 10-tag technical skills grid
- `fun-facts.html` - Creative page with fun facts, hobbies, favorites, and image/video placeholders
- `contact.html` - Contact page with email and GitHub links + contact form
- `style.css` - Pure CSS styling (no external dependencies, no frameworks)
- `vercel.json` - Vercel route and asset caching configuration
