# Dan Onoshko

<img align="right" width="150" height="150" alt="Photo" src="photo.png">

Web Developer

**Location:** Batumi, Georgia

**Email:** [danon0404@gmail.com](mailto:danon0404@gmail.com)

**Telegram:** [@dangreen](https://t.me/dangreen)

**Links:** [Linkedin](https://www.linkedin.com/in/dangreen58/), [GitHub Projects](https://github.com/TrigenSoftware), [GitHub Profile](https://github.com/dangreen)

**Languages:** English (B2), Russian (native)

*[Download CV as PDF](https://raw.githubusercontent.com/dangreen/dangreen/refs/heads/main/Daniil-Onoshko-CV.pdf)*

## Table of Contents

- [About Me](#about-me)
- [Hobbies](#hobbies)
- [How I Got Into Programming](#how-i-got-into-programming)
- [My Articles](#my-articles)
- [Current Open Source Projects](#current-open-source-projects)
- [Employment History](#employment-history)

## About Me

Hi! My name is Daniil, and I am a developer with over 10 years of experience. Most of my production experience is related to creating websites and applications using React.js. Another part of my experience involves creating, maintaining, and improving frontend project infrastructure (build systems, development tools, testing, CI/CD, etc.). An important aspect of my experience is also Open Source: I am a contributor to several projects and have created a few of my own.

I keep up with new technologies and try to apply them in my work. I periodically share my experience through articles and conference talks.

I love creating optimized and accessible interfaces, maintaining project infrastructure, and I am very skilled at refactoring code.

## Hobbies

- Love my cats: a sphynx named Miguel and a Cornish Rex named Marsik
- Collect gaming consoles and games for them
- Modify old gaming consoles
- Sometimes I play computer games
- Love building Lego
- Team Spirit fan 🐉
- Go to the gym

## How I Got Into Programming

In the summer of 2008, my mom sent me to the ["Summer School of Young Programmers"](https://www.iis.nsk.su/edu/school). Since I was not familiar with programming, I was placed in the workshop for the youngest kids. There, I was introduced to the programming language [Scratch](https://scratch.mit.edu/about). I quickly mastered it and realized that I enjoyed programming. I attended the Summer School for the next two summers as well, but without any significant achievements. It became clear that I needed to come prepared, so my mom hired a tutor for me. This tutor was not a computer science teacher but a programmer who wrote software for enterprises using Delphi and tutored on the side. We started learning the basics of Pascal and then moved on to Delphi, where I was very excited to create my first application with a user interface.

Back in 2008, at the Summer School, I learned that besides Windows, there was also Linux, and Apple made not only iPods and iPhones but also computers with their own OS. As a budding geek, I tried various Linux distributions on my own. But one day, I came across a video of a guy installing Mac OS X 10.5 Leopard on, I believe, his Dell laptop. This marked the beginning of my journey into the world of Hackintosh. It wasn't successful on the first try, but I eventually installed Mac OS on my PC.

While studying Delphi, I was eager to apply my knowledge to write a program for Mac OS. I found [Lazarus](https://www.lazarus-ide.org/) — a cross-platform open-source alternative to Delphi. Lazarus was very similar to Delphi, and we continued my lessons using it. Soon, our sessions ended as I had learned the basics, and I began to study what interested me on my own. I was interested in creating a website/repository with kexts (kernel extensions, drivers in Mac OS) for Hackintosh. I decided to build the server-side part using PHP. The site for browsing the catalog was without JS, just HTML and CSS. I had already studied some HTML at the Summer School, and I learned PHP and CSS on the go: if I needed to do something, I searched on Google and did it. In Lazarus, I created a program to populate the kext database. Initially, the database was an XML file on an FTP server, but later I started learning and implementing MySQL. At some point, I wanted to make the site more interactive, so I began learning JS. Before going to camp in 2011, I reviewed the list of workshops, and my choice fell on the Qt development workshop. I decided to see what it was about — and soon, the program for populating the repository was being rewritten in Qt. I never finished the kext repository, but I gained enough knowledge to start freelancing.

## My Articles

- [How to build tree-shakeable JavaScript libraries](https://dev.to/cubejs/how-to-build-tree-shakeable-javascript-libraries-35fa)
- [Why and how to transpile dependencies](https://dev.to/cubejs/why-and-how-to-transpile-dependencies-of-your-javascript-application-3phf)
- [Speed up with Browserslist](https://dev.to/dangreen/speed-up-with-browserslist-30lh)

## Current Open Source Projects

**Maintainer:**

- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) ([PRs](https://github.com/conventional-changelog/conventional-changelog/pulls?page=1&q=is%3Apr+is%3Aclosed+author%3Adangreen)) — a tool to generate changelogs and release notes from a project's commit messages and metadata. Two years ago, I became the maintainer of this project. Since then, I have updated the project's infrastructure and refactored almost all packages in the monorepo: some packages have significantly changed their structure and API; [almost all have been migrated to TypeScript](https://github.com/conventional-changelog/conventional-changelog/issues/1099); old and unnecessary dependencies (such as [lodash](https://www.npmjs.com/package/lodash), [Q](https://www.npmjs.com/package/q), etc.) have been removed.

**Author:**

- [browserslist-useragent-regexp](https://github.com/browserslist/browserslist-useragent-regexp) — a utility to compile [browserslist query](https://github.com/browserslist/browserslist#queries) to a regex to test browser useragent
- [ua-regexes-lite](https://github.com/TrigenSoftware/ua-regexes-lite) — a lite useragent regexes collection. Used in browserslist-useragent-regexp
- [simple-github-release](https://github.com/TrigenSoftware/simple-release-tools/tree/main/packages/simple-github-release) — a simple tool to create GitHub releases. It reads the latest notes from the changelog and creates a release on the GitHub repository with them.
- [argue-cli](https://github.com/TrigenSoftware/Argue) — a thin and strongly typed CLI arguments parser for Node.js

## Employment History

### Senior Frontend Engineer, Visme

**April 2023 - January 2025**

Developer in the infrastructure team. Engaged in refactoring and optimizing frontend code, as well as optimizing and speeding up the project build process.

**Stack:** JavaScript, TypeScript, HTML/CSS, React, Mobx State Tree, Webpack, PNPM, Jest, Node.js.

### Open Source Ecosystem Engineer, Cube

**October 2021 — March 2023**

Supported external open-source data visualization projects to promote the company's main product. Specifically:
- maintained and refactored project infrastructure (build setup, testing tools, CI, etc.)
- improved tree-shaking in projects
- maintained and refactored project code (partially migrated Chart.js to TypeScript, fully rewrote Chartist in TypeScript)
- resolved issues and PRs in project repositories

**Projects:**
- [Chart.js](https://github.com/chartjs/Chart.js) (2.5m downloads/week, [PRs](https://github.com/chartjs/Chart.js/pulls?page=1&q=is%3Apr+is%3Aclosed+author%3Adangreen))
- [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2) (1.5m downloads/week, [PRs](https://github.com/reactchartjs/react-chartjs-2/pulls?q=is%3Apr+is%3Aclosed+author%3Adangreen))
- [svelte-chartjs](https://github.com/SauravKanchan/svelte-chartjs) (50k downloads/week, [PRs](https://github.com/SauravKanchan/svelte-chartjs/pulls?q=is%3Apr+is%3Aclosed+author%3Adangreen))
- [vue-chartjs](https://github.com/apertureless/vue-chartjs) (400k downloads/week, [PRs](https://github.com/apertureless/vue-chartjs/pulls?q=is%3Apr+is%3Aclosed+author%3Adangreen))
- [Chartist](https://github.com/chartist-js/chartist) (100k downloads/week, [PRs](https://github.com/chartist-js/chartist/pulls?q=is%3Apr+is%3Aclosed+author%3Adangreen))

**Stack:** JavaScript, TypeScript, HTML/CSS, React, Vue, Svelte, Webpack, Rollup, SWC, Vite, Vitest, Jest, Storybook, Github Actions, Docusaurus, PNPM, Node.js.

### Frontend Team Lead, Sbermarket

**March 2020 — September 2021**

Frontend Infrastructure Team Lead. Key achievements:
- created and documented a new project structure
- migrated from JavaScript to TypeScript
- added Storybook and created a UI Kit
- implemented a custom SSR server
- added imgproxy for catalog image processing (.web and .avif images with the \<picture\> HTML element)
- redesigned catalog pages

**Stack:** JavaScript, TypeScript, HTML/CSS, SCSS, PostCSS, React, Redux Toolkit, Webpack, Jest, Storybook, Node.js, Ruby on Rails, Docker, imgproxy, Lighthouse, GitLab CI.

### Frontend Team Lead, INGIPRO

**May 2018 — March 2020**

Development of a web application using React. Mentor for Junior and Middle developers, conducted lectures on JavaScript and React.

**Stack:** JavaScript, TypeScript, HTML/CSS, SCSS, PostCSS, React, Redux, Webpack, Jest, Storybook, Node.js, NestJS, Docker, TeamCity CI.

### Frontend Web Developer, LeadCooker Inc

**August 2017 — May 2018**

Development of a Single Page Application from scratch using React.

**Stack:** JavaScript, HTML/CSS, SCSS, PostCSS, React, Redux, Immutable.js, Webpack, Jest, Storybook.

### Full Stack Engineer, CRM Sibiri

**January 2017 — August 2017**

**Stack:** JavaScript, HTML/CSS, Go, Docker.

### Full Stack Engineer, LeadBean

**August 2015 — December 2016**

Development of a drag-and-drop landing page constructor. Was the sole developer responsible for everything from frontend and backend development to CI/CD.

**Stack:** JavaScript, HTML/CSS, SCSS, React, Gulp.js, Mocha, Docker, Selenium, Jenkins, Node.js, Sails.js, PostgreSQL.

### Full Stack Engineer, Clumus

**2015 — August 2015**

**Stack:** JavaScript, HTML/CSS, jQuery, PHP, MySQL.

### Freelance Web Developer, Freelance

**2012 — 2015**

**Stack:** JavaScript, HTML/CSS, jQuery, PHP, MySQL.
