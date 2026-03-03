# Angel Villarreal - Personal Portfolio

A modern, high-performance personal portfolio built with [Astro](https://astro.build/). This site showcases my background, professional projects, and skill set, with a focus on clean architecture and a premium user experience.

## 🚀 Key Features

- **Dynamic Work Gallery**: Projects are managed using Astro Content Collections, with individual pages for each showcase.
- **AI-Powered Background**: A detailed "About" section highlighting over 7 years of full-stack experience, including AI-driven products and agent architectures.
- **Modern UI**: Built with accessible, responsive components and a dark-mode-first aesthetic.
- **Type Safety**: Leveraging TypeScript throughout the project for reliability and better developer experience.
- **Performance**: Near-perfect Lighthouse scores thanks to Astro's zero-JS-by-default approach.

## 📁 Project Structure

```text
/
├── public/              # Static assets (images, favicon, etc.)
├── src/
│   ├── components/      # Reusable UI components (Hero, Nav, CallToAction, etc.)
│   ├── content/         # Markdown/MDX content for projects
│   │   └── work/        # Individual project data files
│   ├── layouts/         # Shared page layouts (BaseLayout.astro)
│   ├── pages/           # Site routes (Home, About, Work, Project details)
│   │   ├── work/        # Dynamic routes for project slugs
│   │   ├── about.astro  # Professional background and education
│   │   ├── index.astro  # Homepage with hero and featured work
│   │   └── work.astro   # Full project listing
│   └── styles/          # Global styles and design tokens
├── astro.config.mjs     # Astro configuration
├── package.json         # Dependencies and scripts
└── tsconfig.json        # TypeScript configuration
```

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: Vanilla CSS (Modern CSS properties, Grid, and Flexbox)
- **Data**: Content Collections (Markdown)

## 🧞 Commands

All commands are run from the root of the project:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local development server at `localhost:4321` |
| `npm run build` | Builds the production site to `./dist/` |
| `npm run preview` | Previews the build locally before deploying |
| `npm run astro` | Runs specific Astro CLI commands |

## 👷 Author

**Angel Villarreal**
- Full-Stack Developer (7+ years)
- Specializing in React, Next.js, NestJS, and AI Implementations.
- [GitHub Repository](https://github.com/Villarreal24/portfolio)
