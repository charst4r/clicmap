# clicmap

trying to create webapp where you can prepare a true-to-size map for events on the epfl campus. hopefully with import and export options.

## structure

this is an Astro project, so this is how it is structured:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── ...
│   ├── components
│   │   └── <component>.astro
│   │		└── ...
│   ├── layouts
│   │   └── <layout>.astro
│   │   └── ...
│   └── pages
│       └── index.astro
│       └── <page>.astro
│       └── ...
└── package.json
```
## commands for devs

from the root of the project:

| command                   | action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | installs dependencies                            |
| `npm run dev`             | starts local dev server at `localhost:4321`      |
| `npm run build`           | build your production site to `./dist/`          |
| `npm run preview`         | preview your build locally, before deploying     |
| `npm run astro ...`       | run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | get help using the Astro CLI                     |

## misc
 
[astro docs](https://docs.astro.build)