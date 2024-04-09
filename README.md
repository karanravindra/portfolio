<h1 align="center">Karan's Personal Portfolio Website</h1>

![Portfolio Preview](https://github.com/karanravindra/portfolio/assets/21176108/f7d55959-f6c5-4d64-bdfd-df80fe3a5f72)
Welcome to the repository for my personal portfolio website. This project is a showcase of my skills and projects, built with a focus on performance, maintainability, and best practices in web development.
## Technology Stack

This portfolio is built using a modern web development stack that ensures a seamless development experience and an optimized final product:

- **Svelte & SvelteKit**: At the core, this website is powered by Svelte and SvelteKit, offering a component-based framework that compiles down to highly efficient vanilla JavaScript. SvelteKit enriches Svelte with features like server-side rendering (SSR) and static site generation (SSG), making the website fast and SEO-friendly. Though I am not employing SSG, SvelteKit provides an AMAZING web development experience.

- **TailwindCSS**: For styling, TailwindCSS is used to rapidly build custom designs without leaving the HTML. This utility-first CSS framework provides the flexibility to style components directly in markup, leading to clearer development patterns and reducing stylesheet complexity.

- **Cloudflare Pages**: Hosting is provided by Cloudflare Pages, ensuring that the website is delivered with speed and security at the forefront. Cloudflare's global CDN and edge network enhance the performance and accessibility of the website across the world.

## Quick Start

To run this project locally, ensure you have Node.js installed, then follow these steps:

```bash
# Clone the repository
git clone https://github.com/karanravindra/portfolio

# Navigate into the project directory
cd portfolio

# Install dependencies
npm install

# Start the development server
npm run dev

# Open the project in a new browser tab automatically
npm run dev -- --open
```

## Building and Deploying

Building a production-ready version of the website is straightforward:

```bash
# Build the project
npm run build

# Preview the production build locally
npm run preview
```

For deployment, the project is configured to automatically deploy to Cloudflare Pages upon pushing to the main branch. Ensure you have set up your project in the Cloudflare Pages dashboard and configured the necessary build settings.

## Contributing

Contributions to improve the website are welcome. Please feel free to fork the repository, make changes, and submit a pull request!

---

This project is built with a focus on using cutting-edge technologies to provide a high-quality web experience. Thank you for visiting!
