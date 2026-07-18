# About Me Portfolio

A personal portfolio and resume website built with [Astro](https://astro.build/), showcasing my experience, education, projects, and technical skills.

## 🎯 Features

- **Hero Section** - Eye-catching introduction
- **About Me** - Personal background and professional summary
- **Tech Stack** - Display of technical skills and technologies
- **Projects** - Showcase of portfolio projects
- **Education** - Academic background and achievements
- **Responsive Design** - Mobile-friendly interface
- **Navigation** - Easy site navigation with navbar and footer

## 🚀 Project Structure

```
about-me/
├── src/
│   ├── pages/
│   │   └── index.astro          # Main landing page
│   ├── components/
│   │   ├── AboutMe.astro        # About section
│   │   ├── Education.astro      # Education section
│   │   ├── Footer.astro         # Footer component
│   │   ├── Hero.astro           # Hero section
│   │   ├── Navbar.astro         # Navigation bar
│   │   ├── Projects.astro       # Projects showcase
│   │   └── TechStack.astro      # Technical skills
│   └── assets/
│       └── icons/               # Icon assets
├── public/                       # Static assets
└── package.json
```

## 🛠️ Tech Stack

- **Astro** - Static site generator
- **Node.js** - Runtime environment (v22.12.0+)

## 📦 Getting Started

### Prerequisites
- Node.js >= 22.12.0
- npm or yarn

### Installation

```bash
npm install
```

### Development

Start the local development server:

```bash
npm run dev
```

The site will open at `http://localhost:4321`

For background mode development:

```bash
astro dev --background
```

Manage background server with:
```bash
astro dev stop       # Stop the server
astro dev status     # Check server status
astro dev logs       # View server logs
```

## 🏗️ Building

Build for production:

```bash
npm run build
```

Output will be generated in the `./dist/` directory.

### Preview Production Build

Preview the production build locally:

```bash
npm run preview
```

## 📚 Available Commands

All commands are run from the root of the project:

| Command           | Action                                    |
| :---------------- | :---------------------------------------- |
| `npm install`     | Install dependencies                      |
| `npm run dev`     | Start dev server at localhost:4321        |
| `npm run build`   | Build production site to ./dist/          |
| `npm run preview` | Preview production build locally          |

## 📖 Learn More

- [Astro Documentation](https://docs.astro.build)
- [Astro Discord Community](https://astro.build/chat)
- [Astro on GitHub](https://github.com/withastro/astro)
