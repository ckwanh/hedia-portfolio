# Hedia Chan – Portfolio

My UX/UI design portfolio, built as a static website and deployed on Vercel.

Live site: hediachan.com · also at hedia-portfolio.vercel.app

## About this project

I'm a UX/UI designer based in Vancouver, studying at IDEA School of Design. I built this site to show my work and to practice turning my own designs into working HTML, CSS and JavaScript.

Each case study covers the problem, solution, process, and my role, team, timeline and tools.

## Starting point and credit

This site started from the open-source template portfolio-for-creatives by James Neufeld (IXD Lab Tech + Instructor), released under GPL-3.0. The template provided the base page layouts, the masonry work grid, the lightbox gallery and the responsive navigation. Thank you, James.

This repo keeps the GPL-3.0 license. The original setup guide has been removed from this README, since it no longer describes my site.

## What I made and changed

Content and design (mine):

All project case studies, writing and images (Dragon City Cafe, PlateSmart, Custom Chimera, Night Market, DisemBARK, Hug a Tree)
Logo, ghost cat illustration and all branding assets
About, Resume and sketchbook pages
Page titles, meta descriptions and site navigation


## How I built it
Tools: VS Code, GitHub, Vercel
AI assistance: I used Claude to help with the content and structure of my project pages, and to help build the tabbed interface on the PlateSmart page.
What I learned: I learned how to build an accessible tabbed interface with HTML, CSS, and JavaScript, including ARIA roles, keyboard arrow-key navigation, and videos that play only when they’re on screen and respect reduced-motion settings. I also got more comfortable using CSS variables and a mobile-first layout to keep a multi-page portfolio consistent.

## Tech
HTML, CSS and JavaScript (no build step)
Lightbox2 for image galleries (MIT)
CSS masonry layout adapted from W3Bits (MIT)
responsive-nav.js for the mobile menu

## Run it locally
Clone the repo:
git clone https://github.com/ckwanh/hedia-portfolio.git
cd hedia-portfolio
Open index.html or work.html in a browser, or use the Live Server extension in VS Code.

Project structure
├── index.html            Landing page
├── work.html             Project grid
├── about.html            About page
├── resume.html           Resume
├── sketchbook.html       Sketches and other work
├── project-*.html        Individual case studies
├── styles/               Stylesheets
├── js/                   Scripts
└── assets/               Images and branding files
License

GPL-3.0, inherited from the original template. See LICENSE.
