<p align="center">
  <h1 align="center">Anamnesis</h1>
<div align="center">
  <img src="static/anamnesis.svg" alt="Anamnesis Logo" width="150" style="filter: invert(1);">
  <br>
  <em>Anamnesis is my personal blog built with <a href="https://gohugo.io">Hugo</a>. As a forgetful person, it serves as my digital notebook<br>to share thoughts, projects, and stories I want to remember</em>
</div>

## Overview

This website is designed with a heavy focus on typography, readability, and a clean user experience. The design utilizes a customized layout to create a focused, balanced landing page. It is fully optimized for both desktop and mobile viewing with a cohesive responsive design.

### Key Features

- **Custom Theme**: Built on top of the <a href="https://github.com/Fabshkiee/hugo-theme-erudite">hugo-theme-erudite</a>, heavily customized to feature a centered hero landing page.
- **Modern Typography**: Uses IBM Plex Sans & Mono for a highly readable, premium feel.
- **Content Management**: Integrated with <a href="https://decapcms.org/">Decap CMS</a> (formerly Netlify CMS) for easy content management directly from the browser (`/admin/`).
- **Responsive Layout**: Full CSS grid and flexbox implementation for seamless scaling across devices.
- **Light/Dark Mode**: Built-in toggle for comfortable reading in any environment.

## Tech Stack

- **Framework**: [Hugo](https://gohugo.io/) (Static Site Generator)
- **Styling**: Vanilla CSS
- **CMS**: Decap CMS
- **Version Control**: Git

## How It Was Made

1. **Foundation**: Started with a fresh Hugo installation and incorporated the Erudite theme template.
2. **Layout Overhaul**: The default index template was rewritten into a dedicated, centered landing page. The grid system was structurally reconfigured to eliminate empty spaces when the Table of Contents isn't active, ensuring the content is perfectly balanced both vertically and horizontally.
3. **Styling & Aesthetics**: Applied significant tweaks to the CSS architecture. Scaled up the hero sections, avatars, and fonts, shifting from strict left-aligned document styles to a more modern, commanding profile view.
4. **CMS Integration**: Configured Decap CMS via the `static/admin/` folder, establishing schema collections for `blogs` and `projects`. This allows for a smooth authoring experience without needing to manually write markdown files in an IDE.

## Local Development

To run this project locally, ensure you have [Hugo Extended](https://gohugo.io/installation/) installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/Fabshkiee/anamnesis-my-blog.git
   cd anamnesis-my-blog
   ```
2. Start the local development server:
   ```bash
   hugo server -D
   ```
3. Open `http://localhost:1313/` to view the site, or `http://localhost:1313/admin/` to access the Content Management System.
