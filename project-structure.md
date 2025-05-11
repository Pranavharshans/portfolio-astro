# Project Structure Documentation
Last updated: 3/6/2025, 9:09:22 PM

## Configuration Files
- `astro.config.mjs` - Astro framework configuration
- `tailwind.config.mjs` - Tailwind CSS configuration
- `tsconfig.json` - TypeScript configuration
- `biome.json` - Biome (formatting/linting) configuration
- `.editorconfig` - Editor configuration for consistent coding style
- `.gitignore` - Git ignore rules
- `.node-version` - Node.js version specification

## Source Code Structure (`src/`)

### Pages (`src/pages/`)
- `index.astro` - Homepage
- `about.astro` - About page
- `posts.astro` - Blog posts listing
- `projects.astro` - Projects showcase
- `post/[slug].astro` - Dynamic post page template

### Layouts (`src/layouts/`)
- `main.astro` - Main layout wrapper
- `post.astro` - Blog post layout

### Components (`src/components/`)
#### General Components
- `about-experience.astro` - Experience section component
- `button.astro` - Reusable button component
- `footer.astro` - Site footer
- `header.astro` - Site header
- `logo.astro` - Logo component
- `page-heading.astro` - Page heading component
- `posts-loop.astro` - Blog posts list component
- `project.astro` - Project card component
- `square.astro` - Square design element
- `square-line.astro` - Line design element
- `square-lines.astro` - Multiple lines design element

#### Homepage Components (`src/components/home/`)
- `projects.astro` - Homepage projects section
- `separator.astro` - Section separator
- `writings.astro` - Homepage blog section

### Collections (`src/collections/`)
- `experiences.json` - Work experience data
- `menu.json` - Navigation menu data
- `projects.json` - Projects showcase data

### Content (`src/content/`)
- `config.js` - Content collections configuration
- `post/` - Markdown blog posts

### Assets
#### CSS (`src/assets/css/`)
- `main.css` - Main stylesheet (includes Tailwind)

#### JavaScript (`src/assets/js/`)
- `main.js` - Main JavaScript file

#### Public Assets (`public/`)
- `favicon.ico` - Site favicon
- `robots.txt` - Search engine crawling rules
- `assets/images/` - Image assets organized by category:
  - `about.jpg` - About page image
  - `cover.png` - Cover image
  - `photo.png` - Profile photo
  - `/experiences/` - Company icons
  - `/posts/` - Blog post images
  - `/projects/` - Project screenshots

## Type Definitions
- `src/env.d.ts` - Environment and Astro type definitions

## Package Management
- `package.json` - Project dependencies and scripts
- `package-lock.json` - NPM lock file
- `pnpm-lock.yaml` - PNPM lock file

## License
- `LICENSE` - Project license file