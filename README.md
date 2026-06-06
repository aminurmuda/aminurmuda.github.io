# Personal Portfolio

My personal website and developer portfolio built with **Astro**, **Tailwind CSS**, and **Native Browser Animations**.

Live Demo: [aminurmuda.github.io](https://aminurmuda.github.io/)

[![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)](https://astro.build/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 🛠️ Tech Stack
- **Frontend:** [Astro](https://astro.build/) (Static Site Generation)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Icons:** [Iconify](https://iconify.design/) via `astro-icon`
- **Deployment:** [GitHub Pages](https://pages.github.com/) (via GitHub Actions)

## 🚀 Getting Started

### Prerequisites
Make sure you have **Node.js** (v22.12.0 or higher) installed on your machine.

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/aminurmuda/portfolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the local development server:
   ```bash
   npm run dev
   ```
5. Build the production site locally:
   ```bash
   npm run build
   ```

## 🌐 Deployment
This portfolio is configured to deploy automatically to GitHub Pages using GitHub Actions. Any push to the `main` branch triggers the workflow in [.github/workflows/deploy.yml](.github/workflows/deploy.yml).

## 📁 Directory Structure
```
├── public/              # Static assets (placeholder.jpg, favicon)
├── src/
│   ├── components/      # Reusable Astro components
│   ├── data/            # JSON files for project and career data
│   ├── layouts/         # Layout templates with Meta tags
│   ├── pages/           # Site routes (index.astro)
│   └── styles/          # Global CSS styles
│   └── config.ts        # Global site configuration
├── astro.config.mjs     # Astro configuration
└── tsconfig.json        # TypeScript configuration
```

## 📝 License
This project is licensed under the [MIT License](LICENSE)
