# Reactor Typescript Template

> To create a web application quickly with React, Redux-toolkit, ReactRouter and Chakra-ui

## Project structure

```bash
project
└───public
│   └───assets
│   │   └───img
│   │   404.html
│   │   favicon.icon
│   │   index.html
│   │   manifest.json
└───src
│   └───configs #configuration file
│   │   │   icon-loader.ts
│   │   │   logger-middleware.ts
│   │   │   store.ts
│   │   │   uitheme.ts
│   └───pages 
│   │   │   Counter.tsx # Demo page
│   │   │   WelcomePage.tsx
│   └───shared
│   │   └───components 
│   │   │   │   Paper.tsx # Paper component
│   │   └───layouts
│   │   │   │   appbar.tsx
│   │   │   │   context.tsx # Context of layout
│   │   │   │   footer.tsx
│   │   │   │   main-layout.tsx
│   │   │   │   sidebar.tsx
│   │   └───reducers
│   │   │   │    counter.reducer.ts # counter reducer
│   │   └───util
│   │   │   │    storage-util.ts # attack sessionstore, localstore
│   │   app.tsx
│   │   index.tsx
│   │   rootReducer.ts
│   │   routes.tsx
└───webpack
│   │   common.config.js
│   │   constants.js
│   │   development.config.js
│   │   production.config.js
│   .eslintignore
│   .eslintrc
│   .prettierignore
│   .prettierrc
│   .babel-plugin-macros.config.js
│   babel.config.js
│   gitignore
│   README.md
│   tsconfig.json
│   webpack.config.js
└───
```

## Config TODO

- [x] React with webpack (typescript, eslint, prettier).
- [x] Integrated a state manager(redux toolkit).
- [ ] Support multiple languages(I18N).
- [x] Support 2 color mode.
- [x] Integrated charka-ui.
- [x] Integrated react-hook-form.
- [ ] Set up e2e test tool (cypress).
- [ ] Integrated PWA with Workbox Inject manifest.
- [x] Make 2 profile (dev and prod).

## How to use?

`npm i`: to install all dependencies.

`npm clean`: to delete node_module and build folder and install all dependencies

`npm run dev`: to run on local.

`npm run build`: to build.
