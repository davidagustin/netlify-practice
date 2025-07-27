# Law & Associates - Professional Law Firm Website

A modern, professional website for Law & Associates built with Astro.js, Tailwind CSS, and deployed on Netlify.

## Live Deployment

🌐 **Live Site**: [https://netlify-practice-one.netlify.app](https://netlify-practice-one.netlify.app)

## Features

- 🏛️ **Professional Design** - Modern, clean design with a dark theme
- 📱 **Responsive Layout** - Mobile-friendly design that works on all devices
- ⚖️ **Practice Areas** - Comprehensive coverage of legal services
- 👥 **Team Profiles** - Attorney profiles and firm information
- 📄 **Legal Resources** - Forms, articles, and educational content
- 📞 **Contact Forms** - Easy consultation booking and communication

## Practice Areas

- Business Law
- Real Estate Law
- Family Law
- Civil Litigation
- Estate Planning
- Criminal Defense

## Astro Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Deploying to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-username/law-associates-website)

## Developing Locally

| Prerequisites                                                                |
| :--------------------------------------------------------------------------- |
| [Node.js](https://nodejs.org/) v18.14+.                                      |
| (optional) [nvm](https://github.com/nvm-sh/nvm) for Node version management. |

1. Clone this repository, then run `npm install` in its root directory.

2. Start the development server:

```bash
npm run dev
```

3. Open your browser and visit [localhost:4321](http://localhost:4321).

## Project Structure

```
src/
├── components/     # Reusable UI components
├── layouts/        # Page layouts
├── pages/          # Website pages
│   ├── blobs/      # Services page
│   ├── index.astro # Home page
│   ├── revalidation.astro # About page
│   └── image-cdn.astro # Resources page
└── styles/         # Global styles
```

## Technologies Used

- [Astro](https://astro.build/) - Static site generator
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Netlify](https://netlify.com/) - Hosting and deployment platform

## License

This project is licensed under the MIT License.
