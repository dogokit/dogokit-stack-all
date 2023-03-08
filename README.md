# Catamyst Stack All

> 🐱 Short URL: [a.catamyst.com/stack-all](https://a.catamyst.com/stack-all)

This is Catamyst's both technical and non-technical stack. The opiniated stack list to manage and build modern apps with web technologies. Which could also help to setup a new team or company tools. These preferences are mainly from [M Haidar Hanif](https://github.com/mhaidarhanif) at [Catamyst](https://github.com/catamyst).

For the simpler version, see [catamyst/stack](https://a.catamyst.com/stack).

## Table of Contents

- [Catamyst Stack All](#catamyst-stack-all)
  - [Table of Contents](#table-of-contents)
  - [Preferences](#preferences)
    - [Quick version](#quick-version)
    - [Short version](#short-version)
    - [Complete version](#complete-version)
  - [Names](#names)
  - [Notes](#notes)
  - [Legend](#legend)
  - [References](#references)
- [Concepts](#concepts)
  - [References](#references-1)
- [Stages](#stages)
  - [Stage 0 → Setup](#stage-0--setup)
    - [References](#references-2)
  - [Stage 1 → Design](#stage-1--design)
  - [Stage 2 → Configuration](#stage-2--configuration)
  - [Stage 2 → Frontend interface](#stage-2--frontend-interface)
  - [Stage 3 → Frontend interaction](#stage-3--frontend-interaction)
  - [Stage 4 → Database, storage, and email](#stage-4--database-storage-and-email)
  - [Stage 5 → Payment 💰](#stage-5--payment-)
  - [Stage 6 → API](#stage-6--api)
  - [Stage 7 → Testing](#stage-7--testing)
  - [Stage 8 → CI/CD](#stage-8--cicd)
- [Work/Management Stack](#workmanagement-stack)
  - [Browser](#browser)
  - [Search Engine](#search-engine)
  - [Utility](#utility)
  - [Multimedia](#multimedia)
  - [Communication](#communication)
    - [External text](#external-text)
    - [External video](#external-video)
    - [Internal text](#internal-text)
    - [Internal video](#internal-video)
  - [Knowledge base](#knowledge-base)
  - [General management](#general-management)
  - [Engineering management](#engineering-management)
  - [Calendar and scheduling](#calendar-and-scheduling)
  - [Community and social media](#community-and-social-media)
- [Jobs](#jobs)
- [General / Full Stack / Frontend \& Backend](#general--full-stack--frontend--backend)
  - [Terminal, shell, prompt](#terminal-shell-prompt)
  - [Code management, version control, auto-merge](#code-management-version-control-auto-merge)
  - [Code editor](#code-editor)
  - [Languages, platforms, runtimes](#languages-platforms-runtimes)
  - [Configuration, formatter, linter](#configuration-formatter-linter)
  - [Generic library for utility](#generic-library-for-utility)
    - [slug](#slug)
- [Frontend Stack](#frontend-stack)
  - [UI, UX, and graphic design](#ui-ux-and-graphic-design)
  - [Asset colors](#asset-colors)
  - [Asset design, diagram, flowchart](#asset-design-diagram-flowchart)
  - [Frontend/web app framework](#frontendweb-app-framework)
  - [Frontend routing](#frontend-routing)
  - [Module bundler, transpiler, minifier, mangler, compressor](#module-bundler-transpiler-minifier-mangler-compressor)
  - [Full-stack web app framework](#full-stack-web-app-framework)
  - [Styling and design system](#styling-and-design-system)
    - [Styling preferences](#styling-preferences)
    - [Pure styling options](#pure-styling-options)
    - [Variant components](#variant-components)
    - [Behavioral components](#behavioral-components)
    - [Styled components](#styled-components)
    - [Misc](#misc)
  - [Data fetching](#data-fetching)
  - [Font hosting](#font-hosting)
  - [Frontend hosting](#frontend-hosting)
  - [Frontend tools](#frontend-tools)
  - [Frontend library](#frontend-library)
  - [Frontend state management](#frontend-state-management)
  - [Frontend assets](#frontend-assets)
- [Backend Stack](#backend-stack)
  - [Platforms and runtimes](#platforms-and-runtimes)
  - [Backend/web server frameworks](#backendweb-server-frameworks)
  - [Web API](#web-api)
  - [Backend as a Service (BaaS) and CMS](#backend-as-a-service-baas-and-cms)
    - [All in One](#all-in-one)
    - [Simple Form](#simple-form)
    - [Backend with Auth](#backend-with-auth)
    - [Notification](#notification)
    - [CMS with Rich Text Editing](#cms-with-rich-text-editing)
    - [Internal Tool](#internal-tool)
  - [Database ORM](#database-orm)
  - [Database Management System (DBMS)](#database-management-system-dbms)
  - [Data Stream](#data-stream)
  - [Database Client](#database-client)
  - [Data Encryption](#data-encryption)
  - [Backend or Full Stack Hosting](#backend-or-full-stack-hosting)
  - [Backend library](#backend-library)
  - [Backend storage for static assets](#backend-storage-for-static-assets)
  - [Backend service](#backend-service)
- [Test](#test)
  - [General](#general)
  - [Unit and Functional](#unit-and-functional)
  - [Functional](#functional)
  - [End to End](#end-to-end)
  - [Utility](#utility-1)
- [Services](#services)
  - [Network](#network)
  - [Payment and finance 💰](#payment-and-finance-)
  - [Payment revenue and subscription analysis](#payment-revenue-and-subscription-analysis)
  - [Business management](#business-management)
  - [Accounting and Invoice](#accounting-and-invoice)
  - [Blog](#blog)
  - [Hiring](#hiring)
  - [URL shortener](#url-shortener)
  - [CRM and chat support](#crm-and-chat-support)
  - [Web and product analytics](#web-and-product-analytics)
  - [Internationalization](#internationalization)
  - [Feature toggle](#feature-toggle)
  - [Monitoring, logging, error tracking, and replayer](#monitoring-logging-error-tracking-and-replayer)
  - [Profiler and session replay](#profiler-and-session-replay)
  - [Uptime monitoring and incident response:](#uptime-monitoring-and-incident-response)
  - [Infrastructure monitoring](#infrastructure-monitoring)
  - [Log management and analysis:](#log-management-and-analysis)
  - [Marketing and newsletter email](#marketing-and-newsletter-email)
  - [Transactional email](#transactional-email)
  - [Containerization](#containerization)
  - [CI/CD](#cicd)
  - [Dependency management](#dependency-management)
  - [Community network](#community-network)
  - [Image editing](#image-editing)
  - [Video editing and sharing](#video-editing-and-sharing)
  - [Audio editing and sharing](#audio-editing-and-sharing)
  - [Shipping](#shipping)
- [References](#references-3)
  - [General](#general-1)
  - [Remix](#remix)
  - [GraphQL](#graphql)
  - [Security](#security)
  - [Boilerplate](#boilerplate)
  - [Workflow](#workflow)
- [Backlog](#backlog)
  - [Company](#company)
  - [Other stacks to evaluate](#other-stacks-to-evaluate)
    - [Related](#related)
- [Legacy versions](#legacy-versions)

## Preferences

### Quick version

TypeScript (HTML+CSS+JavaScript+Node.js included), React, Remix, Tailwind CSS, Ariakit, Prisma ORM, MySQL on PlanetScale, GraphQL, GraphQL Yoga, Pothos Schema, Vercel, Railway.app

### Short version

HTML, CSS, Tailwind CSS, JavaScript, TypeScript, Node.js, npm, React, Remix, Next.js, Ariakit, cva, Prisma ORM, MySQL on PlanetScale, PostgreSQL on Supabase/Neon, Vitest, Playwright, MSW, GraphQL, Express, NestJS, GraphQL Yoga, Pothos Schema, Vercel, Railway.app, Mailjet/Postmark, Google Cloud Platform (GCP).

### Complete version

- JavaScript and TypeScript for programming language
- Node.js for runtime &amp; npm for package manager
  - Golang and Rust ecosystem as altenatives
- HTML for markup language and content structure
- CSS for styling language
  - Tailwind CSS for utility classes
  - cva (Class Variance Authority) for component variants
- React for frontend library and UI components
  - Ariakit, Headless UI, Radix UI for stylable accessible components
- Remix for full stack web framework
  - Remix Router for routing
  - Remix Forms for full-stack form library
- Next.js for alternative web framework
  - Next Router for routing
- Vite for client-side only starter and bundler
- Turbopack or esbuild for bundler
  - swc for transpiler
- Authentication and authorization with
  - Cookie-based sessions
  - Email/Password
  - GitHub
- Express or NestJS for backend framework
  - GraphQL for data query and manipulation language
    - GraphQL Yoga and Envelop for the server and plugin system
  - REST API for other web APIs
- MySQL for relational database on PlanetScale
- Prisma for database ORM
- Pothos for GraphQL schema builder
- MySQL or PostgreSQL for RDBMS
- Vitest and Testing Library for unit and integration testing
- Playwright for functional or e2e testing
- MSW for local third party API request mocking
- EditorConfig, Prettier, ESLint, stylelint, ls-lint, commitlint, lint-staged — for code formatting, linting, static testing
- Git and GitHub for version control, collaboration, and deployment
- Circle CI or GitHub Actions for CI/CD
- Vercel for frontend deployment
- Railway.app for backend or full stack deployment
- ImageKit and Mux for multimedia storage
- Postmark or Mailjet for transactional email
- Google Cloud Platform (GCP) for cloud infrastructure

## Names

We called it the Catamyst Stack or the NORSE Stack. The main defaults in the NORSE Stack are:

- **Node.js** and npm as the main platform and package manager
- **ORM** (Object Relational Mapping), data modeling, and API layer with Prisma and Pothos GraphQL
- **Remix** (React/Vue/Svelte) or Next.js (React) as the full stack layer
- **SQL** (Structured Query Language) DBMS (Database Management System) with MySQL or PostgreSQL.
- **Ecosystem** of libraries and frameworks from the JavaScript and TypeScript community such as Tailwind CSS, Ariakit, etc

![](https://slabstatic.com/prod/uploads/36vdh1kv/posts/images/DWFLbJR_4QWIJYqW3ZKrHvpb.png)

Business-related:

- Slab for note-taking, alternative to Notion and Confluence
- Twist for communication
- Linear for product and software development
- Basecamp / Plutio / Bloom.io for project management
- Outseta for payment management
- Cushion for project balancing
- Wave / Xero / QuickBooks for accounting

## Notes

Keep in mind most the items listed are not used, but the loved ❤️ or most starred ⭐ might be used and recommended. More stars can be added like ⭐⭐⭐ to indicate the importance (0 to 5 stars) or even ❤️ to indicate the utmost priority. The non-starred are just for references, comparison, good alternative, if want to be changed to, waiting for rating, or not evaluated yet.

All of these information also helps the whole team (or even yourself) to choose and change multiple options along the way. Outside of the **Stages** section, the links are annotated to the name of the item.

## Legend

- ⭐ — Rating
- ❤️ — Recommended

## References

- [Catamyst Links](https://catamyst.slab.com/posts/e2jeq5fq) — Public deployments and repositories
- [Catamyst Pages and Features](https://catamyst.slab.com/posts/co0204no) — Public frontend pages

---

# Concepts

- Problem Solving
- Critical Thinking
- First Principles
- Engineering
- Computer Science (CS)
- Software Engineering (SWE)
- Software Architecture (SWA)
- Software Infrastructure (SWI)
- Database
- Deployment
- Containerization
- Career

## References

- [https://pll.harvard.edu/course/cs50-introduction-computer-science](https://pll.harvard.edu/course/cs50-introduction-computer-science?delta=0)

---

# Stages

Here is some quick overview of the preferred or recommended options. Because of the complexity, the setup can go through several stages based on the priorities. In here, there should be no link, annotations, or ratings.

## Stage 0 → Setup

Setup options:

- Laptop
  - Apple → M1 Pro Macbook Pro
  - Linux → Thinkpad
  - Windows → Thinkpad
- Operating System (OS)
  - macOS and iOS → Most reliable
  - Linux and Android → Most flexible
  - Windows → Most popular
- Web Browser
  - Google Chrome → Most popular
  - Brave Browser → Most private
  - Microsoft Edge → Most performant
  - Mozilla Firefox → Most ethical
- Mac-specific
  - Raycast → Command panel
  - Rectangle → Window manager
  - Maccy → Clipboard manager
  - Numi → Calculator
  - Owly → Prevent sleep
  - Macs Fan Control → Change fan speed
  - Hidden Bar / Vanilla → Hide menu bar items
  - iStat Menus → System status
  - KeyCastr → Show keystroke
- Bitwarden + Authy → Credentials &amp; 2FA
- External communication
  - Gmail or Google Workspace → Email service by Google
  - HEY → Email service by Basecamp
- Internal communication
  - Twist → Team chat
  - Email → Backup
- External communication
  - All in One
    - Airtable → Multi purpose business-oriented database
      - Form → Collect submissions data
  - CRM
    - HubSpot → Free CRM + Help Desk
    - Crisp → Paid CRM + Help Desk
  - Email marketing
    - ConvertKit → Free newsletter emails
    - Bento → Paid all-in-one marketing automation platform
  - Community
    - Discord → Casual chat
    - Slack → Casual chat
- GitHub → Git hosting and collaboration
  - Refined GitHub → ?
  - DevHub → Desktop GitHub Notifications &amp; Activities
- Slab → Collaborative notes
- Linear → Internal issue tracking
  - Productlane → User feedback and changelog for Linear
- Clockify → Time tracking
- Around → Video call
- Community → Makerlog, WIP, Twitter, YouTube, etc

### References

- [https://www.robinwieruch.de/mac-setup-web-development](https://www.robinwieruch.de/mac-setup-web-development/)
- [https://dev.to/w3cj/setting-up-a-mac-for-development-3g4c](https://dev.to/w3cj/setting-up-a-mac-for-development-3g4c)

## Stage 1 → Design

- Figma → UI/UX design tool
  - Figma Tokens → ?
  - Tailwind Color Palette → ?
  - Alphredo → Transparent/alpha colors generator
- Excalidraw / Whimsical → Quick diagram
- Favicon.io → Favicon Generator
- Shottr → Screenshot

## Stage 2 → Configuration

- Terminal, shell, prompt
  - Alacritty → The fastest terminal app
  - Warp → The modern terminal app
  - zsh → Terminal shell
  - Starship.rs → Terminal prompt
- Git → Version control
  - diff-so-fancy →
  - Conventional Commit → ?
- Repository
  - Semantic Versioning (semver) → ?
  - Semantic Release (semantic-release) → Fully automated version management and package publishing
  - Contributor Covenant → ?
  - Release Please → ?
- Package manager
  - Homebrew → macOS
  - apt → Ubuntu
- asdf → Runtime manager
  - Volta → JavaScript tool manager
- Node.js → JavaScript runtime
  - npm → Node.js package manager
  - pnpm → npm alternative that is fast and disk space efficient
  - Openbase → compare open-source packages
- TypeScript → Superset of JavaScript with type safety
- VS Code → Code editor
- EditorConfig → Common coding style
- Prettier → Code formatter
- ESLint → JavaScript linter
- Stylelint → CSS linter
- ls-lint → File name linter
- commitlint → Commit message linter
- lint-staged → Staged changes linter
- Doppler → Universal Secrets Platform
- Plop → File generator

## Stage 2 → Frontend interface

- React → Frontend UI library
- Remix → Full stack web framework on React/Vue
- Next.js → Full stack web framework on React
- Astro → Static site generator with React/Vue/Svelte/Solid
- Tailwind CSS → Utility CSS framework
  - UI Colors → Generate color shades
  - cva → variant management
- PostCSS → CSS transformer
- Ariakit → Unstyled components
- Headless UI → Unstyled, fully accessible UI components
- Radix UI → Accessible UI component primitives
  - tailwindcss-radix
- Icons
  - Phosphor Icons → Application icons
  - React Icons → All in one
  - Font Awesome → Social media icons
- UI components
  - Markdoc → Markdown renderer
  - Prism.js + Prism React Renderer → Code syntax highlighting renderer
    - Shiki → Code syntax highlighting alternative
  - Monaco Editor → Code editor
- State management
  - Jotai →
  - Zustand → ?
- Nextra / Slate Docs → Documentation
- Vercel → Deployment for speed
  - Axiom → Logging
- Railway.app → Deployment for backup
- Cloudflare / Google Domains → Domain and DNS
- Dr. Link Check → Links check

## Stage 3 → Frontend interaction

- Status monitoring
  - Pulsetic → ?
  - Better Uptime → ?
  - Instatus → ?
- Form, input, text area
  - Remix Form → for Remix
  - React Hook Form → Complex client-side form library
  - tiny-invariant → provide descriptive errors in development but generic errors in production.
  - Tiptap / Typist / Lexical → Rich text editor
- User and product analytics
  - Google Analytics 4 → Most popular analytics
  - Splitbee → Friendly analytics
  - Posthog → Product analytics
  - Pirsch → Beautiful analytics
  - Plausible → Powerful analytics
  - MixPanel → Simple analytics
- App analytics and error reporting
  - Sentry → App analytics and error tracking
  - LogRocket → ?
  - Metronome → Remix insights
- Dependency monitoring
  - DepFu → Common
  - Snyk → Security
- Feature toggle
  - Growthbook → Feature flagging and experimentation

## Stage 4 → Database, storage, and email

- Prisma → ORM (Object Relational Mapper)
  - Argon2 / bcrypt
- MySQL on PlanetScale → Relational database
- PostgreSQL on Neon → Relational database
  - Dashibase → Quick dashboard
- Snaplet → Development and backup
- Arctype → SQL Client
- X → Object storage
- ImageKit → Image Storage
- Mux → Video storage
- Postmark → Transactional email
- Mailjet → Transactional email
- Basedash → Internal tooling

## Stage 5 → Payment 💰

- Paddle → Payments infrastructure for Internatioanal
- Lemon Squeezy
- Midtrans → Payment gateway for Indonesia
- PayPal → Alternative payment method
- Gumroad → Backup

## Stage 6 → API

- HTTPie &amp; Hoppscotch → API client
- GraphQL → Data query and manipulation language for API
  - Pothos → ?
- Nexus → ?
- Axios → REST API client
- urql → GraphQL client
- Payload CMS / GraphCMS → Content management system
- GraphCDN → GraphQL CDN

## Stage 7 → Testing

- Falso/Faker → Generate fake data
- Vitest → ?
- Cypress → ?
- Mock Service Worker (MSW) → ?

## Stage 8 → CI/CD

- GitHub Actions → Build checks
  - (orang build)
  - Changeset
  - Codecov
- CodeFactor → Code review
- Docker → Container

---

# Work/Management Stack

## Browser

- Google Chrome —?
  - uBlock Origin —?
  - Bitwarden —?
  - Raindrop —Bookmark management
- Brave Browser — ?
- Microsoft Edge — ?
- Mozilla Firefox — ?
- [Min Browser](https://minbrowser.org) — A fast, minimal browser that protects your privacy
- [WebCatalog](https://webcatalog.io/) — ?

## Search Engine

- Google — ?
- DuckDuckGo — ?
- Bing — ?
- Brave Search — ?

## Utility

- Credentials
  - Bitwarden — ?
  - Authy — ?
- Mac-related
  - Raycast — Blazingly fast, totally extendable launcher. It lets you complete tasks, calculate, share common links, and much more.
  - Maccy — macOS clipboard manager
  - Numi — Beautiful calculator app for Mac
  - Rectangle — Move and resize windows in macOS using keyboard shortcuts or snap areas
  - Owly — ?
  - Macs Fan Control— ?
  - iStat Menus — ?
  - KeyCastr — ?
  - Cursor Pro — ?
- Writing
  - Grammarly — ?
  - [QuillBot AI](https://quillbot.com/) — Paraphrasing Tool

## Multimedia

- VLC — ?
- Calibre — ?

## Communication

### External text

- Gmail / Google Account ❤️⭐⭐⭐ — Access to Google services
  - Google Calendar — ?
  - Google Drive — ?
  - YouTube — ?
- HEY Email ❤️⭐⭐⭐⭐⭐ — ?
  - [Hey Email + Google Calendar](https://merecivilian.com/heyhey/)
- ProtonMail ⭐⭐ — ?
- Superhuman ⭐⭐⭐ — The Fastest Email Experience Ever Made

### External video

- StreamYard — ?
- [Restream](https://restream.io/) — Create and Multistream Live Video
- [Riverside](https://riverside.fm/) — ?
- [Melon](https://melonapp.com/) — Login &amp; Start Streaming

### Internal text

- Twist ❤️⭐⭐⭐⭐⭐ — ?
- Slack — ?

### Internal video

- Around.co — Video calls loved by extraordinary teams
- Zoom.us — ?
- Claap — Record quick videos of your screen, get contextual feedback, and make decisions. The modern way to align hybrid teams. Less Meeting. More doing.

## Knowledge base

- Slab ❤️⭐⭐⭐ — for primary team knowledge base
- Outline ⭐⭐ — Team knowledge base &amp; wiki
- Notion ⭐⭐ — for legacy tracks/topics/lessons
- Reflect ⭐ — keep track of your notes, books, and meetings

## General management

Generally for tracking issue, feedback, roadmap, changelog, and time.

- GitHub Issues ⭐⭐⭐⭐ — public issue tracking and management
- Linear ⭐⭐⭐⭐⭐ — internal team issue tracking and management to handle the priority feature development.
- Roadmap and changelog
  - Productlane ⭐⭐⭐⭐ — Linear-based public roadmap, user feedback, and changelog
  - Headwayapp — ?
  - Canny — ?
  - Productboard — ?
- Clockify ⭐⭐⭐ — The most popular free time tracker for teams

## Engineering management

- Sleuth — ?

## Calendar and scheduling

- Calendly ❤️⭐ — ?
- Cal.com ❤️⭐ — Open source Calendly alternative (previously Calendso)
- Cron calendar ❤️⭐ ⭐⭐— Next-generation calendar for professionals and teams.
- Rise calendar — ?
- SavvyCal — ?
- Nook Calendar — ?

## Community and social media

Especially for profile pictures.

- GitHub — ?
- GitLab — ?
- LinkedIn — ?
- Twitter — ?
- Facebook — ?
- Instagram — ?
- YouTube — ?
- Discord — ?
- Showwcase — ?
- Slack — ?
- Makerlog — ?
- WIP — ?
- Polywork — ?
- Stack Overflow — ?
- Hashnode — ?
- Dev.to — ?
- Gravatar — ?

# Jobs

- Remote OK — ?
- Grow Remote — ?

# General / Full Stack / Frontend &amp; Backend

[https://github.com/catamyst/catamyst](https://github.com/catamyst/catamyst)

## Terminal, shell, prompt

- Terminal app
  - Universal
    - [Alacritty](https://alacritty.org/) ⭐⭐⭐ — Cross-platform, OpenGL terminal emulator
      - alacritty-themes CLI
    - [Hyper™](https://hyper.is/) ⭐⭐⭐ — Terminal built on web technologies by Vercel
  - Mac
    - iTerm2 ⭐⭐ — ?
    - Warp ⭐⭐ — ?
- Terminal shell
  - zsh ⭐⭐⭐ — ?
    - [Antibody](https://getantibody.github.io/) — Shell plugin manager made from the ground up thinking about performance.
- Terminal prompt
  - Starship.rs ⭐⭐⭐ — Cross-Shell Prompt. The minimal, blazing-fast, and infinitely customizable prompt for any shell
- Terminal commands
  - [asdf-vm/asdf](https://asdf-vm.com/) ⭐⭐⭐ — Extendable version manager with support for Ruby, Node.js, Elixir, Erlang &amp; more. Manage multiple runtime versions with a single CLI tool
  - [clvv/fasd](https://github.com/clvv/fasd) ⭐⭐⭐ — Fasd (pronounced similar to &quot;fast&quot;) is a command-line productivity booster. Fasd offers quick access to files and directories for POSIX shells. It is inspired by tools like autojump, z and v.
  - [Volta](https://volta.sh/) ⭐⭐⭐ — The Hassle-Free JavaScript Tool Manager
- Remote login
  - OpenSSH — ?

## Code management, version control, auto-merge

- Git ❤️⭐⭐⭐ — the most popular version control
  - diff-so-fancy — ?
  - [Conventional Commit](https://www.conventionalcommits.org/) — Specification for adding human and machine readable meaning to commit messages
  - [Release Please](https://github.com/googleapis/release-please) — Automates CHANGELOG generation, the creation of GitHub releases, and version bumps for your projects.
- GitHub ❤️⭐⭐⭐ — the best Git hosting on the planet
  - Refined GitHub ⭐⭐⭐ — ?
  - [DevHub](https://devhubapp.com/) ⭐⭐⭐ — Desktop GitHub Notifications &amp; Activities
  - [Neat](https://neat.run/) ⭐ — Supercharge your GitHub workflow
- Git tools
  - degit ⭐ — Straightforward project scaffolding, to the info in README
  - GitFlow — structured branching model and workflow for Git
  - PR auto-merge
    - Kodiak ⭐
    - Mergify ⭐
- Doppler ❤️⭐⭐⭐ — Universal Secrets Platform
- [Plop](https://plopjs.com/) — Consistency Made Simple. Little tool that saves you time and helps your team build new files with consistency
- Repository, document, versioning, contributing
  - [Semantic Versioning (semver)](https://semver.org/) ⭐⭐⭐⭐⭐ — set of rules and requirements that dictate how version numbers are assigned and incremented
  - [Semantic Release (semantic-release)](https://semantic-release.gitbook.io/semantic-release/) ⭐⭐⭐⭐ — Fully automated version management and package publishing
  - [Standard Readme](https://github.com/RichardLitt/standard-readme) ⭐⭐⭐⭐ — standard style for README files
  - [Contributor Covenant](https://www.contributor-covenant.org/) — A Code of Conduct for Open Source and Other Digital Commons Communities

## Code editor

- VS Code — ?
  - VS Code Preferences
  - VS Code Themes
  - VS Code Extensions
    - [dsznajder/vscode-react-javascript-snippets](https://github.com/dsznajder/vscode-react-javascript-snippets)
- NeoVim — ?
- StackBlitz — ?
- CodeSandbox — ?

## Languages, platforms, runtimes

- TypeScript — ?
- JavaScript — ?
- Node.js — ?
- npm — ?
  - Yarn — ?
  - pnpm — Fast, disk space efficient package manager
  - Openbase — ?

## Configuration, formatter, linter

- EditorConfig ⭐⭐⭐ — ?
- Prettier ⭐⭐⭐⭐⭐ — ?
- ESLint ⭐⭐⭐⭐⭐ — ?
  - eslint-config-airbnb
  - @remix-run/eslint-config
  - prettier-eslint
  - eslint-plugin-tailwindcss
- [Stylelint](https://stylelint.io/) ⭐⭐⭐⭐⭐ — A mighty, modern linter that helps you avoid errors and enforce conventions in your styles
  - stylelint-config-prettier
- [ls-lint](https://ls-lint.org/) ⭐⭐⭐⭐⭐— File name linter
- commitlint ⭐⭐⭐— Commit message linter

## Generic library for utility

- dayjs ⭐ — ?
- cuid ⭐ — ?
- jsonwebtoken ⭐ — ?
- validator ⭐ — ?
- Lodash ⭐ — ?
- [is-online](https://github.com/sindresorhus/is-online) ⭐ — Check if the internet connection is up
- [is-reachable](https://github.com/sindresorhus/is-reachable) ⭐ — Check if servers are reachable
- [humanize-list](https://github.com/johno/humanize-list) ⭐ — Comma delimit an array for human readability, the Oxford comma is optional.

### slug

- [limax](https://github.com/lovell/limax) ⭐⭐⭐ — ?
- slugify ⭐⭐ — ?

---

# Frontend Stack

[https://github.com/catamyst/web](https://github.com/catamyst/web)

## UI, UX, and graphic design

- Figma ⭐⭐⭐ — The collaborative interface design tool
  - Typescale — Harmonious typographic scales, directly from your design tool
  - Figma Tokens — ?
- [Lunacy](https://icons8.com/lunacy) ⭐⭐⭐ — Free Design Software for Win, Mac, Linux
- Framer ⭐⭐⭐ —
- InVision ⭐⭐ —
- Sketch ⭐⭐ —
- Penpot ⭐⭐ —

## Asset colors

- [Alphredo](https://alphredo.app/) — Alpha colors generator

## Asset design, diagram, flowchart

- Excalidraw — ?
- Whimsical — ?
- tldraw — ?
- FigJam by Figma — ?
- Miro — ?
- XMind — ?

## Frontend/web app framework

- React ⭐⭐⭐⭐⭐ — UI library/framework
  - TSX/TypeScript — ?
  - JSX/JavaScript — ?
  - HTML — ?
  - CSS — ?
- React Native ⭐⭐⭐ — ?
  - Expo ⭐ — ?

## Frontend routing

- React Router — ?
- TanStack Location — ?
- [wouter](https://github.com/molefrog/wouter) — ?

## Module bundler, transpiler, minifier, mangler, compressor

- esbuild — ?
- Vite — ?
  - [vite-plugin-ssr](https://vite-plugin-ssr.com/) — ?
- Turbopack — ?
- Webpack — ?
- Babel — ?
- swc — ?
- Terser —?

## Full-stack web app framework

- Remix ❤️⭐⭐⭐⭐⭐ — ?
  - esbuild as bundler — ?
- Remix Packages
  - React Router v6 — ?
    - history — ?
    - query-string — ?
    - qs — ?
  - remix-seo ❤️⭐ —
  - remix-pwa ❤️⭐ — PWA integration &amp; support for Remix
  - remix-utils ⭐ —
  - remix-themes ⭐ — An abstraction for themes in your Remix app.
  - remix-auth ⭐ — inspired by Passport
  - [remix-i18next](https://github.com/sergiodxa/remix-i18next) — The easiest way to translate your Remix apps
  - remix-image — ?
  - remix-forms — ?
  - remix-tailwind — research first
  - remix-query ⭐ — Keep your loader data in sync in your component without reloading the page
- Next.js — ?
  - NextAuth.js — ?
  - Outstatic — A Static Site CMS for Next.js
- RedwoodJS — ?

## Styling and design system

Template, starter kit, or boilerplate:

- [Rewinds](https://rewinds.mhaidarhanif.com) ❤️⭐⭐⭐⭐⭐ — Remix Tailwind Starter Kit by M Haidar Hanif
- [Vitesse](https://vitesse.netlify.app/) — Opinionated Vite Starter Template by Anthony Fu
- [ts-nextjs-tailwind-starter](https://tsnext-tw.thcl.dev/) — Next.js + Tailwind CSS + TypeScript Starter by Theodorus Clarence

### Styling preferences

- React Universal = Tailwind CSS + Headless UI + Radix UI + family of libraries
- React CSS-in-JS = Stitches + Radix UI + Radix Colors

### Pure styling options

- Tailwind CSS ❤️⭐⭐⭐⭐⭐ — A utility-first CSS framework for rapid UI development
  - [UI Colors](https://uicolors.app) — Tailwind CSS Color Shades Generator &amp; Editor
  - PostCSS — CSS transformer
  - @tailwindcss/typography
  - @tailwindcss/forms
  - @tailwindcss/line-clamp
  - @tailwindcss/aspect-ratio
- UnoCSS ⭐⭐⭐ — ?
  - It's actually better than Tailwind, just the ecosystem is still new, like there is no editor plugin yet
- [Master CSS](https://css.master.co/) ⭐⭐⭐ — A Virtual CSS language with enhanced syntax. Efficiently build your UI and design system with HTML only.

### Variant components

- cva (Class Variance Authority) — component variants

### Behavioral components

- Headless UI ❤️⭐⭐⭐⭐ — Unstyled, fully accessible UI components
- Radix UI ❤️⭐⭐⭐⭐ — Accessible component system that replicate most Headless UI components
  - @radix-ui/react-scroll-area
- Reach UI — ?
- Ariakit — ?
- Downshift — ?
- React Select — ?
- [TanStack Table v8](https://tanstack.com/table/v8) / React Table — Headless UI for building powerful tables &amp; datagrids
- Tailwind components
  - Tailwind UI ⭐ — Beautiful UI components
    - Only for references, as VechaiUI and daisyUI provide a more organized UIs
  - daisyUI — Tailwind CSS Components
  - Vechai UI ❤️⭐⭐⭐ — React Tailwind CSS Components
  - [Tailblocks](https://tailblocks.cc/) — ?
  - Hyper UI — ?
  - Tail-kit / tailwind-kit.com
  - tailwindcomponents.com
  - kitwind.io
  - tailblocks.co
  - merakiui.com
  - tailwindtoolbox.com

### Styled components

- Stitches ⭐⭐ — CSS-in-JS library and theming solution
  - Performant and can customize variants easily
  - Replace emotion and styled-components
  - Can extract Tailwind CSS config into Stitches config
  - Replicate most Tailwind UI components
  - Can implement multiple themes than just light and dark mode
- emotion — ?
- styled-components — ?

### Misc

- Radix Colors ⭐⭐— accessible color system with light and dark theme
  - Only when using Radix UI and Stitches together
  - Not when using Tailwind CSS
- Existing design system and components for inspirations
  - NextUI ⭐⭐⭐ — for UI components based on Stitches
  - Chakra UI ⭐⭐⭐ — for flexible UI components
  - Mantine — for complex ready to use components
  - NativeBase — ?
  - UI Kitten— ?
  - React Native Elements— ?
  - Eva Design System — Deep learning color generator

## Data fetching

- Remix built-in loader and action with fetch
- [Axios HTTP](https://axios-http.com/) ⭐⭐⭐ — Promise based HTTP client for the browser and Node.js
- [urql](https://formidable.com/open-source/urql/) ❤️⭐⭐⭐ — &quot;Universal React Query Library&quot; is a blazing-fast minimal GraphQL client. The highly customizable and versatile GraphQL client for React, Svelte, Vue, or JavaScript.
  - Can perform in Remix Loader
  - Can replace graphql-request or Apollo
- graphql-request ⭐ — GraphQL client
  - Only when urql is too much
- [SWR](https://swr.vercel.app/) — React Hooks for Data Fetching
- TanStack Query / React Query — ?

## Font hosting

- Google Fonts **⭐⭐⭐** — ?
- fontbit.io **⭐ —** Simple and privacy-friendly Google Fonts proxy

## Frontend hosting

- Vercel ❤️⭐⭐⭐⭐ —
  - not free for organizations but free for personal and the fastest out there.
  - [https://vercel.com/changelog/remix-projects-can-now-be-deployed-with-zero-configuration](https://vercel.com/changelog/remix-projects-can-now-be-deployed-with-zero-configuration)
- Netlify ❤️⭐⭐⭐⭐ — ?
- Cloudflare Pages ⭐⭐⭐ — ?
  - Free for organizations but slightly slower than Vercel. A bit harder to debug because they don't really use Node.js
  - [https://blog.cloudflare.com/remix-on-cloudflare-pages](https://blog.cloudflare.com/remix-on-cloudflare-pages/)
- Cloudflare Workers ⭐⭐ — ?

## Frontend tools

- Dr. Link Check — Broken Link Checker

## Frontend library

- Hooks
  - usehooks-ts — ?
- Forms
  - React Hook Form — ?
  - Formik — ?
  - React Final Form — ?
- Icons
  - [Icônes](https://icones.js.org/) — Icon Explorer with Instant searching, powered by Iconify
  - Iconify ❤️⭐⭐⭐⭐⭐ — ?
  - React Icons ❤️⭐⭐⭐ — ?
  - Phosphor Icons ❤️⭐⭐⭐ — ?
  - Remix Icon ⭐⭐ — ?
  - Feather Icons ⭐⭐ — ?
  - Boxicons ⭐ — ?
  - Ionicons ⭐ — ?
  - Font Awesome ⭐ — ?
  - Game Icons — ?
  - Simple Icons — 2000+ Free SVG icons for popular brands
- Component documentation
  - Storybook ⭐⭐⭐⭐⭐ — component management
  - Bit.dev — ?
- Markdown
  - [Markdoc](https://markdoc.io/) ⭐⭐⭐⭐ — A powerful, flexible, Markdown-based authoring framework
  - MDX / [mdxjs](https://mdxjs.com/) — Markdown for the component era
  - [marked](https://marked.js.org/) ⭐⭐⭐ — ?
  - [remark](https://remark.js.org/) — ?
  - [markdown-to-jsx](https://github.com/probablyup/markdown-to-jsx) ⭐⭐⭐ — ?
  - [markdown-it](https://markdown-it.github.io/) — ?
  - [html-react-parser](https://github.com/remarkablemark/html-react-parser) — ?
- Code syntax highlighting
  - Prism.js ⭐⭐⭐⭐⭐ —?
    - Prism React Renderer — ?
  - highlight.js ⭐⭐⭐ — ?
    - React Syntax Highlighter —?
  - [Shiki](https://shiki.matsu.io/) ⭐⭐⭐ — ?
- Markdown documentation generator
  - Nextra — ?
  - Slate — ?
- Emoji
  - Twemoji &amp; react-twemoji ⭐⭐⭐ — ?
  - OpenMoji — ?
- Rich text editor / WYIWYG editor
  - [Tiptap](https://tiptap.dev/) ❤️⭐⭐⭐⭐⭐ — Headless WYSIWYG Text Editor
    - [Typist](https://typist.doist.dev/) ❤️⭐⭐⭐⭐⭐ — Rich Editor based on Tiptap
  - [Quill.js](https://quilljs.com/) ❤️⭐⭐⭐ — Your powerful rich text editor
  - [Lexical](https://lexical.dev/) ❤️⭐⭐⭐ — An extensible text editor framework that does things differently
  - Jodit ⭐ — ?
  - Slate.js ⭐— ?
- Animation library
  - [AutoAnimate](https://auto-animate.formkit.com/) — Add motion to your apps with a single line of code
  - Framer Motion ⭐ — animated component
  - react-spring — ?
  - anime.js — ?
  - Velocity.js — ?
- Gesture and drag and dop library
  - [use-gesture](https://use-gesture.netlify.app/) — ?
  - [dnd kit](https://dndkit.com/) — dnd kit – a modern drag and drop toolkit for React
- Charting library
  - D3.js — ?
  - Vega — ?
- Diagramming library
  - D2 — ?
    - Text to diagram — ?
  - MermaidJS — ?
  - PlantUML — ?
  - Graphviz — ?
- 2D and 3D engine
  - [Matter.js](https://brm.io/matter-js/) — 2D physics engine for the web
  - [Three.js](https://threejs.org/) — JavaScript 3D Library based on WebGL
  - [GreenSock](https://greensock.com/) — GSAP (GreenSock Animation Platform) — Professional-grade animation for the modern web
- Parallax library — [https://openbase.com/categories/js/best-react-parallax-libraries](https://openbase.com/categories/js/best-react-parallax-libraries)
  - react-parallax
  - simpleParallax.js — a JavaScript library for parallax effects
  - parallax.js — ?
- Slide deck
  - [slidev](https://sli.dev/) — Presentation Slides for Developers
  - [Gamma](https://gamma.app/) — Write like a doc Present like a deck
- Video creation
  - [Remotion](https://www.remotion.dev/) — Write videos in React
- Keyboard shortcuts
  - [kbar](https://kbar.vercel.app/) — command+k interface for your site
  - CommandBar ⭐⭐⭐ — ?
- Maps
  - Mapbox
  - react-map-gl — Mapbox GL JS for React
- Math typesetting
  - [KaTeX](https://katex.org/) — The fastest math typesetting library for the web
- Files and images
  - Filepond — ?
  - Pintura Image Editor — ?
- Slide or carousel
  - [Swiper](https://swiperjs.com/) — The Most Modern Mobile Touch Slider or Carousel
- Blockchain and web3
  - RainbowKit — ?
- Others
  - react-device-detect — Detect device, and render view according to detected device type
  - react-responsive — CSS media queries in React for responsive design, and more

## Frontend state management

- Jotai — ?
- Zustand — ?
- Redux — ?
- XState — ?
- Recoil — ?

## Frontend assets

- Shottr — ?
- [CleanShot X](https://cleanshot.com/) — ?
- Image optimizer
  - TinyPNG/TinyJPG ⭐⭐⭐⭐⭐ — Compress multiple WebP, PNG, and JPEG images intelligently
  - Squoosh ⭐⭐⭐ — Make images smaller using best-in-class codecs, right in the browser
- Favicons
  - [Favicon.io](https://favicon.io/favicon-converter/) — The best Favicon Generator (completely free)
  - [Real Favicon Generator](https://realfavicongenerator.net/) — ?
- [Open Peeps](https://www.openpeeps.com/) — Hand-Drawn Illustration Library
- [Descript](https://www.descript.com/) — All-in-one audio/video editing, as easy as a doc.
- [Bannerbear](https://www.bannerbear.com/) — API for Automated Image and Video Generation
  - neg4n/next-api-og-image — ?
- [Senja](https://senja.io/) — The #1 Tool to Collect, Manage &amp; Share Testimonials
  - [Testimonial.to](https://testimonial.to/) - Collect and embed testimonials in minutes

---

# Backend Stack

[https://github.com/catamyst/api](https://github.com/catamyst/api)

## Platforms and runtimes

- Node.js ⭐⭐⭐⭐⭐ — ?
- Deno ⭐⭐⭐⭐ — ?
- Golang ⭐⭐⭐ — ?
- Rust ⭐⭐ — ?

## Backend/web server frameworks

- Express.js ⭐⭐⭐⭐⭐ — ?
  - cors — ?
  - morgan — ?
- Fastify ⭐⭐⭐ — ?
- tinyhttp ⭐ — 0-legacy, tiny &amp; fast web framework as a replacement of Express
- NestJS ⭐ — ?
- AdonisJS — ?
- Hapi — ?
- [Fresh](https://fresh.deno.dev/) for Deno — ?

## Web API

- GraphQL ⭐⭐⭐⭐⭐ — ?
  - Internal GraphQL for most dynamic data management. Because even big techs are using it (Shopify, Github, Medium, Docker, Twitter, Airbnb, and Paypal)
  - GraphQL Code Generator ⭐ — ?
  - GraphCDN ⭐ — ?
  - Nexus GraphQL ⭐ — ?
  - [Apollo GraphQL](https://www.apollographql.com/) ⭐ — Supergraph: unify APIs, microservices, and databases in a composable graph. Unifies GraphQL across your apps and services, unlocking faster delivery for your engineering teams.
- REST API ⭐⭐⭐ — ?
  - Still needed in case of an alternative or public API release
- tRPC — ?
- gRPC — ?
  - Only when there is a budget and performance issue
- WebSocket — ?
  - Socket.io — ?
  - [soketi](https://soketi.app/) — Simple, fast, and resilient open-source WebSockets server. 📣
  - [LiveBlocks](https://liveblocks.io/) — ?
- Client
  - Hoppscotch ⭐⭐⭐⭐⭐ — API client for REST API and GraphQL
  - Postman — ?
  - Insomnia — ?
  - Paw — The most advanced API tool for Mac

## Backend as a Service (BaaS) and CMS

### All in One

- Airtable — ?
  - All purpose database
  - Form
  - CRM
  - ATS, Applicant Tracker

### Simple Form

- Jotform — ?
- [EmailJS](https://www.emailjs.com/) — ?
- [Getform.io](https://getform.io/) — ?
- [FabForm.io](https://fabform.io/) — ?

### Backend with Auth

- Firebase ⭐⭐ — ?
  - Rowy — Low-code backend on Google Cloud and Firebase. Instant Airtable-like UI for managing your database on your own cloud.
- [Supabase](https://supabase.com/) ⭐⭐⭐ — The Open Source Firebase Alternative
  - [Dashibase](https://dashibase.com/) ⭐⭐⭐ — No-code dashboards with Supabase
- Nhost — ?
- Strapi — ?
- Kontenbase — Easily create backend API, auth, and storage in less than one minute without coding.
- [AWS Amplify](https://aws.amazon.com/amplify) — ?
- [Backendless](https://backendless.com/) — ?
- [back4app](https://www.back4app.com/) — ?

### Notification

- Novu — Notification management simplified

### CMS with Rich Text Editing

- Hygraph / GraphCMS ⭐⭐⭐⭐⭐ — content management system in static assets
- Payload CMS ⭐⭐⭐ — ?

### Internal Tool

- [Retool](https://retool.com/) — ?
- ToolJet — ?
- [Budibase](https://budibase.com/) — ?
- [Basedash](https://www.basedash.com/) ⭐ — Collaborative Database Editing
- [Appsmith](https://www.appsmith.com/) ⭐ — Build &amp; self-host internal tools
- [Metabase](https://metabase.com/) — ?
  - The backend written in Clojure which contains a REST API

## Database ORM

- Prisma ORM ⭐⭐⭐ — ?
  - [Prismaliser](https://prismaliser.app/) — ?
- Sequelize — ?
- TypeORM — ?
- Bookshelf.js — ?
- Knex.js — ?

## Database Management System (DBMS)

- MySQL ⭐⭐⭐⭐ — ?
  - MySQL on PlanetScale ⭐⭐⭐⭐⭐ — ?
- PostgreSQL ⭐⭐⭐⭐ — ?
  - Postgres.app for Mac ⭐⭐⭐⭐⭐ — ?
  - PostgreSQL on Railway.app ⭐⭐⭐⭐⭐ — ?
  - PostgreSQL on Render ⭐⭐ — ?
- Redis — ?
  - Redis on Upstash ⭐⭐⭐⭐ — ?
  - Redis on Railway.app ⭐⭐⭐ — ?
  - Redis on Render — ?
  - RedisInsight — ?
- CockroachDB ⭐⭐⭐ — ?
- MongoDB ⭐⭐⭐ — ?
  - Realm — ?
- [SurrealDB](https://surrealdb.com/) ⭐⭐ — ?
- Snaplet — ?

## Data Stream

- Kafka — ?
  - Kafka on Upstash — ?
- Fluvio — ?

## Database Client

- Arctype SQL Client — Free SQL Editor for Developers
- TablePlus — ?
- [Medis](https://getmedis.com/) — ?

## Data Encryption

- Argon2 ❤️⭐⭐⭐ — ?
- Bcrypt ⭐⭐ — ?

## Backend or Full Stack Hosting

- Railway.app ⭐⭐⭐⭐⭐ — ?
- [Render.com](https://render.com/) ⭐⭐⭐ — Cloud Application Hosting for Developers
  - Need to check if compatible with Remix
- [Buddy.works](https://buddy.works/) — The easiest CI/CD. Ever. Buddy is the most effective way to build better apps faster. The DevOps Automation Platform
- Fly.io — ?
- Heroku — ?
- Cyclic.sh — ?
- Google Compute Engine — ?
- Amazon EC2 — ?

## Backend library

- [geoip-lite/node-geoip](https://github.com/geoip-lite/node-geoip) — Native Node.js implementation of MaxMind's GeoIP API

## Backend storage for static assets

Includes object storage, block storage, file storage, archive storage, and data transport.

- Images
  - Gravatar — ?
  - ImageKit ⭐ — ?
- Videos
  - muse.ai ⭐ — The power of video made simple for you
  - VdoCipher — Secure Video Hosting for Business
  - bunny.net — The Content Delivery platform that truly Hops!
- Anything
  - Cloudinary — ?
  - Google Cloud Storage — ?
  - Amazon S3 — ?
  - Azure Blob Storage — ?
  - Vultr Object Storage — ?
  - Linode Object Storage — ?
  - [DigitalOcean Spaces](https://www.digitalocean.com/products/spaces) — S3-Compatible Cloud Object Storage
  - Wasabi Cloud Storage — ?

## Backend service

Especially for background process.

- Temporal.io ⭐ — ?
- Quirrel ⭐ — ?
- EasyCron — ?
- Healtchecks.io — ?
- Dkron — ?
- Privy.io — Simple APIs to manage user data off-chain

---

# Test

## General

- [Testing Playground](https://testing-playground.com/) — Simple and complete DOM testing playground that encourage good testing practices.

## Unit and Functional

- Vitest ⭐⭐⭐⭐ — ?
  - happy-dom — ?
- Jest ⭐⭐⭐ — ?
  - Jest Preview — ?
- React Testing Library ⭐⭐ — ?

## Functional

- Tomato ⭐ — ?

## End to End

- Cypress ⭐⭐⭐ — ?

## Utility

- Mock Service Worker (MSW) ⭐⭐⭐⭐⭐ — ?
- [Falso](https://ngneat.github.io/falso/) ⭐⭐⭐⭐⭐ — ?
- [Faker](https://fakerjs.dev/) ⭐⭐⭐ — ?

---

# Services

## Network

- Cloudflare Registrar ⭐ — ?
  - Migrated from Uniregistry/GoDaddy
- Cloudflare DNS ⭐ — ?

## Payment and finance 💰

- International
  - Outseta ❤️⭐⭐⭐⭐ — ?
  - Paddle ❤️⭐⭐⭐⭐ — ?
    - [https://snappify.io/blog/step-by-step-guide-for-paddle-integration](https://snappify.io/blog/step-by-step-guide-for-paddle-integration)
  - [Lemon Squeezy](https://lemonsqueezy.com)
  - Quaderno ⭐⭐⭐ — ?
  - Stripe ⭐⭐⭐ — ?
    - Recurly — ?
  - Gumroad ⭐ — ?
  - Flurly ⭐ — ?
  - PayPal ⭐ — ?
  - Plaid — ?
- Singapore
  - HitPay — ?
  - Eway Singapore — ?
- Malaysia
  - iPay88 — ?
  - Gkash — ?
- Indonesia
  - Midtrans ⭐⭐⭐ — ?
  - Xendit ⭐⭐⭐ — ?
  - Durianpay ⭐⭐ — ?
  - Mayar ⭐ — ?

## Payment revenue and subscription analysis

Subscription data platform and analytics.

- MRR.io ❤️⭐⭐⭐ — Keep track of your Monthly Recurring Revenue
- ChartMogul ⭐⭐⭐ — Subscription Analytics Platform
- [ProfitWell](https://www.profitwell.com/) ⭐ — Subscription business financial metrics

## Business management

- [Cushion](https://cushionapp.com) — Forecasting for freelancers
- [Plutio](https://www.plutio.com) — One app to run your business and get work done
- Bloom.io ❤️⭐⭐⭐ — ?

## Accounting and Invoice

- Wave Accounting ❤️⭐⭐⭐ — ?
- Xero — ?
- FreshBooks — ?
- QuickBooks — ?
- invoicely — ?
- Square Invoices — ?

## Blog

- Dev.to ⭐⭐⭐⭐ — ?
  - Forem — ?
- Hashnode ⭐⭐⭐⭐ — ?
- [Ghost.org](https://ghost.org/) ⭐⭐⭐ — Turn your audience into a business
- Medium ⭐⭐ — ?

## Hiring

- Homerun — Where hiring comes together

## URL shortener

- Rebrandly ⭐ — ?

## CRM and chat support

- [Crisp](https://crisp.chat/) ❤️⭐⭐⭐⭐⭐ — #1 Messaging Platform For Startups and SMBs
- [HubSpot](https://www.hubspot.com/products/crm) ❤️⭐⭐⭐⭐ — Best Free CRM Software for Businesses
- Chatwoot ⭐⭐⭐ — ?
- Groove ⭐⭐⭐ — ?
- Clay ⭐⭐⭐ — ?

## Web and product analytics

- Open source
  - Posthog ❤️⭐⭐⭐⭐ — Host your own product analytics
    - `posthog-js`, `posthog-node`
  - Pirsch ❤️⭐⭐⭐⭐— Cookie-Free and Privacy-Friendly Web Analytics
    - 30-day free trial, `pirsch-sdk`
  - Plausible ❤️⭐⭐⭐ — Simple, privacy-friendly Google Analytics alternative
    - 30-day free trial, `plausible-tracker`
  - Matomo ⭐⭐ — The Google Analytics alternative that protects your data
  - Umami ⭐ — simple. fast. beautiful. own your website analytics.
- Closed source
  - Splitbee (Acquired by Vercel) ❤️⭐⭐⭐⭐ — Your all-in-one analytics and conversion platform
    - `splitbee-js`
  - [Mixpanel](https://mixpanel.com/) ❤️⭐⭐⭐ — Product Analytics for Mobile, Web, &amp; More
  - Simple Analytics ❤️⭐⭐⭐ — The privacy-first Google Analytics alternative
    - 14-day free trial
  - Fathom Analytics ❤️⭐⭐⭐ — Website analytics without compromise
    - 7-day free trial, `fathom-client`
  - [Amplitude](https://amplitude.com/) ⭐⭐⭐ — The Digital Optimization System
  - June.so ⭐⭐ — Product-Led Analytics
    - `@june-so/analytics-next`
  - [Microsoft Clarify](https://clarity.microsoft.com/) ⭐⭐ — Free Heatmaps &amp; Session Recordings
  - Google Analytics ⭐⭐ — Analytics Tools &amp; Solutions for Your Business
  - Hotjar ⭐ — Website Heatmaps &amp; Behavior Analytics Tools
  - Fullstory ⭐ — Build a More Perfect Digital Experience
  - heatmap — Real-time analytics for your website

## Internationalization

- i18next ⭐⭐⭐⭐⭐ — ?

## Feature toggle

- Growthbook ❤️⭐⭐⭐ — ?
- LaunchDarkly ⭐⭐⭐ — ?
- [flagged](https://github.com/sergiodxa/flagged) — ?

## Monitoring, logging, error tracking, and replayer

- [Sentry](https://sentry.io/) ❤️⭐⭐⭐⭐ — ?
- [Axiom](https://www.axiom.co/) ❤️⭐⭐⭐⭐ — ?
- Checkly — Delightful Active Monitoring for Developers
- [Highlight.run](https://www.highlight.run/) ⭐⭐⭐ — Reproduce end-to-end user sessions to better understand their application
- [Metronome.sh](https://metronome.sh/) ⭐⭐⭐ — Insights tailored for Remix

## Profiler and session replay

- OpenReplay ⭐⭐⭐ — ?
- LogRocket ⭐ — ?
- Replay ⭐ — ?

## Uptime monitoring and incident response:

- Pulsetic ❤️⭐⭐⭐ — ?
- Better Uptime ❤️⭐⭐⭐ — ?
- Instatus ❤️⭐⭐⭐ — ?
- Upptime ⭐ — Free uptime monitor and status page powered by GitHub
- UptimeRobot — ?
- Lightstep — ?

## Infrastructure monitoring

- DataDog ⭐ — ?
- New Relic — ?

## Log management and analysis:

- [Loggly](https://www.loggly.com/) ⭐ — ?

## Marketing and newsletter email

- [ConvertKit](https://convertkit.com/) ❤️⭐⭐⭐⭐ — The creator marketing platform, especially for newsletter emails
- [Bento](https://bentonow.com/) ⭐⭐⭐⭐ — All-in-one marketing automation platform. Marketing Tracking and Automation Platform For Ecommerce
- [CustomerIO](https://customer.io/) ⭐⭐⭐ — Marketing Automation for the Whole Customer Lifecycle
- [SendStack](https://getsendstack.com/) ⭐⭐⭐ — Privacy-first newsletter platform
- [Loops.so](https://loops.so/) ⭐⭐⭐ — Email made easy. Create, send and track beautiful email campaigns your users will love
- [Drip](https://www.drip.com/) ⭐⭐⭐ — The Ecommerce Revenue Engine. Email and SMS marketing for growing ecommerce brands.
- [ActiveCampaign](https://www.activecampaign.com/) ⭐⭐⭐ — #1 Customer Experience Automation Platform
- [Intercom](https://www.intercom.com/) ⭐⭐⭐ — The Engagement OS. The modern customer communications platform that unifies every aspect of the customer journey, from conversion to engagement to support
- [HubSpot](https://www.hubspot.com/) ⭐⭐⭐ — Inbound Marketing, Sales, and Service Software
- [Keap](https://keap.com)® ⭐⭐⭐ — fka Infusionsoft — CRM, Sales &amp; Marketing Automation
- [GetResponse](https://www.getresponse.com/) ⭐⭐⭐ — Get Started with a Free Marketing Platform
- [Klaviyo](https://www.klaviyo.com/) ⭐⭐ — Email Marketing &amp; SMS Automation Platform
- [Buttondown](https://buttondown.email/) ⭐⭐ — The easiest way to write your newsletter. Small, elegant tool for producing newsletters
- [MailerLite](https://www.mailerlite.com/) ⭐⭐ — Create Email Marketing Your Audience Will Love
- [Keila](https://www.keila.io/) ⭐ — Open Source Email Newsletters Easy &amp; Reliable
- [Revue](https://www.getrevue.co/) ⭐ — Editorial newsletter tool for writers and publishers
- [MailChimp](https://mailchimp.com/) ⭐ — Marketing, Automation &amp; Email Platform

## Transactional email

- [Mailjet](https://www.mailjet.com/) ❤️⭐⭐⭐⭐ — Email Delivery Service for Marketing &amp; Developer Teams
- [Postmark](https://postmarkapp.com/) ⭐⭐⭐ — Fast, Reliable Email Delivery Service, SMTP, API
- [DMARC Digests](https://dmarcdigests.com/) — DMARC Monitoring to Protect Your Email Deliverability and Combat Spoofing and Phishing
- Amazon SES ⭐ — ?
- Nodemailer ⭐ — ?
- [Sendgrid](https://github.com/novuhq/novu/tree/main/providers/sendgrid) ⭐ — ?
- [Mailgun](https://github.com/novuhq/novu/tree/main/providers/mailgun) ⭐ — ?
- [SES](https://github.com/novuhq/novu/tree/main/providers/ses) ⭐ — ?
- [NodeMailer](https://github.com/novuhq/novu/tree/main/providers/nodemailer) ⭐ — ?
- [Mandrill](https://github.com/novuhq/novu/tree/main/providers/mandrill) ⭐ — ?
- [Sendinblue](https://github.com/novuhq/novu/tree/main/providers/sendinblue) ⭐ — ?
- [EmailJS](https://github.com/novuhq/novu/tree/main/providers/emailjs) ⭐ — ?
- SparkPost ⭐ — ?

## Containerization

- Docker ⭐ — ?
- Kubernetes — ?
  - Restack — Creating the next generation of open source developers

## CI/CD

- GitHub Actions ⭐⭐⭐ — ?
  - Meercode — ?
- [CodeFactor](https://www.codefactor.io/) ⭐⭐⭐ — Automated Code Review for C#, C++, Java, CSS, JS, Go, Python, Ruby, TypeScript, Scala, CoffeeScript, Groovy, C, PHP, Dockerfile, Shell, YAML, HTML, Vue, Swift, Kotlin, PowerShell, Dart and R source code
- [Buddy Works](https://buddy.works/) — ?
- Circle CI ⭐ — ?
- Heroku CI — ?
- Travis CI — ?
- AppVeyor — ?

## Dependency management

- Depfu ⭐⭐⭐ — Automated dependency updates done right. More configurable than Dependabot
- Snyk ⭐⭐⭐ — Security updates
- AccessLint ⭐ — Automated and continuous web accessibility testing

## Community network

- Luma / Lu.ma ⭐⭐⭐⭐ — ?
- Mighty Network ⭐⭐ — ?

## Image editing

- Ray.so — Create beautiful images of your code
- BrandBird Studio — Easy, fast image editing for founders. Turn boring screenshot into beautiful sharable images

## Video editing and sharing

- ScreenFlow — ?
- Loom — ?
- [Grain](https://grain.com/) — Capture &amp; Share Insights from Customer Meetings. The easiest meeting insights tool to understand and communicate the needs of your customers.
- tl;dv — ?

## Audio editing and sharing

- Yac — ?

## Shipping

- Indonesia
  - Shipper — ?
  - Biteship — ?
  - Lalamove — ?

---

# References

## General

- [MDN Web Docs](https://mdn.dev/)
- [Free for Dev](https://free-for.dev/)

## Remix

- [Load only the data you need in Remix - Sergio Xalambrí](https://sergiodxa.com/articles/load-only-the-data-you-need-in-remix)

## GraphQL

- [How to GraphQL](https://www.howtographql.com/)
- [Working with Remix, GraphQL, and GraphCMS](https://graphcms.com/blog/working-with-remix-and-graphql)

## Security

- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)

## Boilerplate

- [Remix Stacks](https://remix.run/docs/en/v1/pages/stacks)
- [Bedrock Boilerplate by Max Stoiber](https://bedrock.mxstbr.com)

## Workflow

- [Kodiak Prior Art / Alternatives](https://kodiakhq.com/docs/prior-art-and-alternatives)

---

# Backlog

- [Mac Setup for Web Development [2022] - Robin Wieruch](https://www.robinwieruch.de/mac-setup-web-development)

## Company

- [Firstbase](https://www.firstbase.io/) — Start and grow a US business from anywhere
- [Devyce](https://devyce.com/) — The modern business phone system.

## Other stacks to evaluate

- [Upload.io](https://upload.io/) — Image
- [Lyra](https://lyrajs.io/) — Fast, in-memory, typo-tolerant, full-text search engine written in TypeScript.
- [Fuse.js](https://fusejs.io/) — Powerful, lightweight fuzzy-search library, with zero dependencies.
- Algolia — ?
- Slate API Docs generator — ?
- MinIO — ?
- Replicache — ?
- Ashby HQ — [https://app.ashbyhq.com/access](https://app.ashbyhq.com/access)
- Runway — [https://runway.com](https://runway.com/)
- Daydream — [https://daydream.co](https://daydream.co/)
- Pocus — [https://www.pocus.com](https://www.pocus.com/)
- Airplane — [https://www.airplane.dev](https://www.airplane.dev/)
- Teamflow — [https://www.teamflowhq.com](https://www.teamflowhq.com/)
- Endgame — [https://www.endgame.io](https://www.endgame.io/)
- Matter for Slack — [https://matterapp.com](https://matterapp.com/)
- Kona — [https://www.heykona.com](https://www.heykona.com/)
- Reclaim AI — [https://reclaim.ai](https://reclaim.ai/)
- Hazelcast — [https://hazelcast.com](https://hazelcast.com/)
- Vector.dev — [https://vector.dev](https://vector.dev/)
- Deel — ?
- Turing.com — ?
- [https://delighted.com/](https://delighted.com/)
- [https://fibery.io/](https://fibery.io/)
- [https://github.com/conventional-changelog/standard-version](https://github.com/conventional-changelog/standard-version)
- [https://roughnotation.com/](https://roughnotation.com/)
- [https://react-hot-toast.com/](https://react-hot-toast.com/)
- [https://github.com/evilmartians/lefthook](https://github.com/evilmartians/lefthook)
- [https://github.com/sharkdp/hyperfine](https://github.com/sharkdp/hyperfine)
- [https://drawsql.app/](https://drawsql.app/)
- [https://www.heykona.com/](https://www.heykona.com/)
- [https://www.entri.com/](https://www.entri.com/)
- ⭐⭐⭐ [https://usabilityhub.com/](https://usabilityhub.com/)
- [https://training.visualizevalue.com/feed](https://training.visualizevalue.com/feed)
- [https://arc.io/](https://arc.io/)
- [https://rootly.com/](https://rootly.com/)
- [https://www.stackhawk.com/](https://www.stackhawk.com/)
- [https://withpersona.com/](https://withpersona.com/) — Identity Verification Solutions for Every Business | Persona
- [https://lucaong.github.io/minisearch/](https://lucaong.github.io/minisearch/) — Tiny and powerful JavaScript full-text search engine for browser and Node
- [Bree](https://jobscheduler.net) — The best job scheduler for Node.js and JavaScript with cron, dates, ms, later, and human-friendly support.
- [https://bitmovin.com](https://bitmovin.com/) — APIs to encode, play and analyze video
- [https://www.deepl.com/translator](https://www.deepl.com/translator) — DeepL Translate: The world's most accurate translator
- [PicWish](https://picwish.com/) — Online Background Remover
- [https://www.meilisearch.com/](https://www.meilisearch.com/)
- [https://github.com/valeriansaliou/vigil](https://github.com/valeriansaliou/vigil)
- [https://www.scaleway.com/en/](https://www.scaleway.com/en/)
- [https://www.hetzner.com/](https://www.hetzner.com/)
- [https://stepzen.com/](https://stepzen.com/) — GraphQL-as-a-Service: Build GraphQL faster, run better, scale seamlessly
- [https://components.ai/](https://components.ai/) — Components AI — A new way to explore generative design systems
- [https://randoma11y.com/](https://randoma11y.com/)
- [https://toolness.github.io/accessible-color-matrix/](https://toolness.github.io/accessible-color-matrix/)
- [https://www.waldo.com/](https://www.waldo.com/)
- [https://www.protailwind.com/tutorials](https://www.protailwind.com/tutorials)

### Related

- [https://mentorcruise.com/](https://mentorcruise.com/)
- [https://huntr.co/bootcamps](https://huntr.co/bootcamps) - cohort
- [https://www.teachfloor.com/](https://www.teachfloor.com/) - cohort
- [https://maven.com/](https://maven.com/)

---

# Legacy versions

The legacy versions are in [Stack (Legacy)](https://catamyst.slab.com/posts/5puqbz0u)

Long ago this was indexed in an Airtable base
