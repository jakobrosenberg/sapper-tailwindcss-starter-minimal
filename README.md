# sapper-tailwindcss-starter-minimal template
#### The purpose of this template is to keep it as close to the original Sapper template as possible

@apply can be used in both css files and .svelte style tags.


```bash
#to install
npx degit "jakobrosenberg/sapper-tailwindcss-starter-minimal" my-app
cd my-app
npm install # or yarn!
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.

Consult [sapper.svelte.dev](https://sapper.svelte.dev) for help getting started.


There's no purgecss. Instructions may be added.

#### To enable more plugins, simply install depencies and extend postcssPlugins
```javascript
const postcssPlugins = [
    require("postcss-import")(),
    require("postcss-url")(),
    require("tailwindcss")("./tailwind.config.js"),
    require("autoprefixer")({ browsersList: ["defaults"] })
    ...
]
```
