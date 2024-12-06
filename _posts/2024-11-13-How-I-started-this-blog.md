---
title: "How I started this blog"
date: 2024-11-13
categories:
  - posts
tags:
  - web development 
  - jekyll
  - docker
  - github
  - vscode devcontainers
toc: true
toc_label: "Table of Contents"
toc_icon: "bookmark"
excerpt: "Learn how I built this blog in minutes using Jekyll, Docker, GitHub, and VSCode DevContainers. Discover my journey, solutions, and insights into creating a fast, secure, and mobile-friendly platform for showcasing projects."
header:
  teaser: "/assets/images/How-I-started-this-blog.png"
---
<!-- Pakkende Titel -->
# How I started this blog.
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#)
[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white)](#)
[![Jekyll](https://img.shields.io/badge/Jekyll-C00?logo=jekyll&logoColor=fff)](#)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?logo=github&logoColor=white)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)](#)
[![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white)](#)

<!-- ## Introductie -->
## Introduction – Why I started this blog.
The past years, I gained experience in various projects. I enjoy myself immersing in new concepts and technologies and quickly get the hang of them. I realise this by quickly creating a proof of concept and maintaining a very short feedback loop. I like to make a lot of small steps and learn from them. Or as some people say:

> "The man who moves a mountain begins by carrying away small stones" (Confucius, 551–479 BCE).

I would like to use this blog to showcase the projects, however, I don't want to spend too much time on the blog itself. I want to focus on the content. 

<!-- ## Probleemstelling -->
## Problem statement – Setting the requirements for the blog.
To showcase the projects, I have some functional requirements for the blog and prioritized them as follows via [MoSCoW](https://community.atlassian.com/t5/App-Central-articles/Understanding-the-MoSCoW-prioritization-How-to-implement-it-into/ba-p/2463999) (Must have, Should have, Could have, Won't have):

The blog ...
1. *must* be fast. – Nobody likes a slow website.
2. *must* be secure. – I don't want to worry about security.
3. *should* be easy to maintain. –  I'd rather spend time on the content.
4. *should* be easy to navigate. – I want to make it easy for people to find the content.
5. *should* be easy to read on mobile devices and desktops. – I want to reach as many people as possible.
6. *should* be neat and clean. – I want to make a good professional impression.
7. *could* be easy to find on the internet. – I want to reach as many people as possible.
8. *could* be cost-effective to host. – Initially, I prefer a free hosting solution to minimize expenses. If the blog gains traction, I can consider upgrading to a paid plan for additional features and scalability.

<!-- ## Data of Aanpak -->
## Solution – Jekyll, Docker, GitHub, and VSCode DevContainers.
I prefer to not reinvent the wheel and use existing solutions. I found Jekyll a good solution that meets my requirements and also my personal skill level. 

1. A static website is fast because it doesn't need to generate pages on the fly. Moreover, I only need text and images to be shown, no advanced interactive things. – *Jekyll* is a good solution for this.
2. Jekyll can be securely hosted on github pages [more info](https://talk.jekyllrb.com/t/recent-vulnerabilities-in-jekyll-and-jekyll-dependencies/2219/3) Moreover, static websites are less vulnerable to attacks. – *GitHub* is a good solution for this. 
3. Jekyll can be efficiently utilized within VSCode DevContainers, making it accessible for anyone with coding experience to quickly get started. For more information on the benefits, refer to [this article](https://javascript.plainenglish.io/the-benefits-of-using-dev-containers-for-local-development-3bb8f78b800). See also the [documentation](https://code.visualstudio.com/docs/devcontainers/containers) of vscode – *VSCode DevContainers* is an excellent solution for this.
4. Jekyll has a lot of [themes](https://jekyll-themes.com/free) that are easy to customize. – *Jekyll*
5. The Minimal Mistakes theme, developed by Michael Rose automatically adjusts the website to mobile friendly format. – *Jekyll - Minimal Mistakes theme*
6. The Minimal Mistakes theme is neat and clean. – *Jekyll - Minimal Mistakes theme*
7. Minimal Mistakes has been SEO optimised [source](https://mmistakes.github.io/minimal-mistakes/docs/posts/) and jekyll has plugins to improve the findability of the website. [source](https://medium.com/@shantoroy/how-to-effectively-perform-search-engine-optimization-to-a-jekyll-minimal-mistakes-blog-post-9c3a17865eca) – *Jekyll*
8. GitHub pages is free to host static websites. Github could also generate the website by itself without using docker as can be read [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 

I recommend reading the linked articles if you would like better understand the tech side. If you prefer to get started quickly, follow the instructions of the following blogs: 

- [Create a Minimalism GitHub Page for Your Data Science Portfolio in 30 Minutes ](https://chriskhanhtran.github.io/posts/portfolio-tutorial/) by Cris Tran
- [Building my Data Science Portfolio using Jekyll and Netlify](https://www.ibienenwoko.com/blog/my-first-website/) by Ibiene Obuoforibo
- [The Portfolio that Got Me a Data Scientist Job](https://towardsdatascience.com/the-portfolio-that-got-me-a-data-scientist-job-513cc821bfe4) by Matt Chapman

<br>  
<br>

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/meeslindhout/meeslindhout.github.io)  
You could also copy my blog by forking my repository on GitHub via the link above.

<!-- ## Analyse en Resultaten -->
## Analysis and Results – What I learnt and some interesting findings.
### Don't overcomplicate things. Just [KISS](https://en.wikipedia.org/wiki/KISS_principle)!
Try not to make it harder than it is. Start with the basics and add features when you need them. I started with a simple blog and added features when I needed them. KISS stands for "Keep it simple, stupid" or "Keep it stupid simple". It's a design principle that states that systems work best when they are kept simple rather than made complicated. It originated in the U.S. Navy in 1960.

### The paradox of choice: Why more is less.
I realised that there are many different ways to create a blog. It's easy to get lost in the possibilities as there are many different tutorials and tools available. Eventually you get lost in the possibilities and maybe never start. I found it interesting to discover this phenomenon. You can read about the [paradox of choice](https://works.swarthmore.edu/fac-psychology/198/) or watch this famous [TED talk](https://www.ted.com/talks/barry_schwartz_on_the_paradox_of_choice) and how it can affect decision-making. I tried to keep the number of choices to a minimum. Instead, I chose the one that met my requirements. It could be that there are better solutions, but I'm happy with the one I chose. 

### "Copycat" a proven concept, but make it your own.
Use something that has been proven to work. I used the Minimal Mistakes theme, which is a popular theme for Jekyll. I also got inspiration from Chris Tran. I made adjustments to make it my own (but of course did not use his content). For transparency, all sources that I used are mentioned in this blog post or in the readme file on GitHub.

<!-- ## Conclusie -->
## Conclusion – The blog has is up and running, what's next :eyes:?
Creating this blog has been an exciting and educational journey. It allowed me to combine technical tools like Jekyll, Docker, and GitHub while aligning with my personal philosophy of starting small, iterating quickly, and focusing on continuous improvement. The result is a platform that reflects not just my projects but also my problem-solving approach and adaptability.

<!-- ## Call-to-Action -->
To anyone reading this: If you're interested in my work, have questions, or see potential for collaboration, feel free to connect with me. Interested in more content? Check out my other posts. You can use the tags to filter on specific technologies or topics.