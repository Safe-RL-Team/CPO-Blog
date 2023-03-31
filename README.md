

## Link to our code repository: https://github.com/Safe-RL-Team/cpo

This is where you can find our technical implementation

### Setup

- [ ] Clone your fork or copy of this repository: `git clone …`
- [ ] [Install `npm` (Node Packet Manager)](https://docs.npmjs.com/getting-started/installing-node#installing-npm-from-the-nodejs-site). If you're on a Mac and have `brew`: `brew install node` will do the job.
- [ ] `cd post--example` into the root directory of this project.
- [ ] `npm install` to install dependencies.
- [ ] Execute `npm run dev` to run a development server that autoreloads when you make changes to the article ("hot-reloading"). The console output will link you to a hot-reloading preview of the article.

Components and diagrams are stored in `src`. The `.html` files are [svelte](https://svelte.technology/guide) components, the `.js` files are compilation endpoints that are also defined in `webpack.config.js`. These compiled endpoints are then consumed by hand authored `.ejs` files in `src`, such as `index.ejs` which contains your content. For most articles you can simply use the provided `index.ejs` for your text, `index.js` to instantiate diagrams, and `.html` svelte files to create them.


