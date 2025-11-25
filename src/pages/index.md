---
layout: ../layouts/IndexLayout.astro
content_blocks:
  - type: hero
    heading: Marketing website done with Astro
    content: Astroship is a starter template for startups, marketing websites & landing pages. Built with Astro.build and TailwindCSS. You can quickly create any website with this starter.
    color: "#ffffff"
    image: /images/hero.png
  - type: features
    heading: Everything you need to start a website
    description: Astro comes batteries included. It takes the best parts of state-of-the-art tools and adds its own innovations.
    features:
      - title: Bring Your Own Framework
        description: Build your site using React, Svelte, Vue, Preact, web components, or just plain ol' HTML + JavaScript.
        icon: bx:bxs-briefcase
      - title: 100% Static HTML, No JS
        description: Astro renders your entire page to static HTML, removing all JavaScript from your final build by default.
        icon: bx:bxs-window-alt
      - title: On-Demand Components
        description: Need some JS? Astro can automatically hydrate interactive components when they become visible on the page.
        icon: bx:bxs-data
      - title: Broad Integration
        description: Astro supports TypeScript, Scoped CSS, CSS Modules, Sass, Tailwind, Markdown, MDX, and any other npm packages.
        icon: bx:bxs-bot
      - title: SEO Enabled
        description: Automatic sitemaps, RSS feeds, pagination and collections take the pain out of SEO and syndication. It just works!
        icon: bx:bxs-file-find
      - title: Community
        description: Astro is an open source project powered by hundreds of contributors making thousands of individual contributions.
        icon: bx:bxs-user
  - type: logos
    heading: Works with your technologies
    icons:
      - name: simple-icons:react
      - name: simple-icons:svelte
      - name: simple-icons:astro
      - name: simple-icons:tailwindcss
        size: size-8 md:size-16
      - name: simple-icons:alpinedotjs
        size: size-8 md:size-16
      - name: simple-icons:vercel
  - type: cta
    heading: Build faster websites.
    description: Pull content from anywhere and serve it fast with Astro's next-gen island architecture.
    buttonText: Get Started
    buttonLink: "#"
---
