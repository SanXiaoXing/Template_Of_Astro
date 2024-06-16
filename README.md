# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)]()

[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)]()

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)]()

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.ico	(头像存放)
├── src/
│   ├── components/	(组件布局)
│   │   ├── sections/ (组件卡片)
│   │   │	├── AboutMe.astro
|	|	|	├── IntroCard.astro
|	|	|	├── Now.astro
|	|	|	├── TimeZoneCard.astro
|	|	|	└── StudyCard.astro
│   │   ├── ui/	(组件效果)
│   │   │	├── card.tsx
│   │   │	├── button.tsx
│   │   │	└── badge.tsx
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └──	HeadSEO.astro
│   ├── layouts/	(基本布局)
│   │   └── BaseLayout.astro
│   ├── pages/	(界面)
│   │   └── index.astro
│   └── styles/	(css存放)
│   │   └── globals.css
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
