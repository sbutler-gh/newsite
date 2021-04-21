# This is a template for a website based on Svelte (because it allows you to do amazing things) and Indieweb standards, with perfectmotherfucking accessibility and minimalism

**Get started:**

1. Fork or clone this repository for yourself, and follow the Svelte instructions (see **create-svelte**) below to get it setup
2. Follow the Indiewebify steps (https://indiewebify.me/) to get everything setup
3. Edit the content of existing files/folders, or create new files folders as desired
4. Push it to GitHub/GitLab and host it with Netlify


> Follow the Indiewebify steps (https://indiewebify.me/) to get everything setup

Hcard and Hentry components have been configured in src/lib.  You should adjust these for yourself.

Then, you can insert them in any page like this:

<Hcard />
<Hentry />

You can see an example of how to include this in src/index.svelte

> Edit the content of existing files/folders, or create new files folders as desired

Currently, in routes, there is a  posts folder and a projects folder.

You may have many files in posts to represent different posts.  Just add those files in that folder, and they will be accessible like this:

yourdomain.com/posts/filename

If you want to create a "home" page for that folder — like a catalog of all of your posts — then make that an "index" file inside that folder.

When someone vistist  yourdomain.com/posts, they will see the index.svelte file in the posts folder.  When someone visits yourdomain.com/yourfolder, they will see the index.svelte file in the yourfolder folder.

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Svelte apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `node build`. To use a different adapter, add it to the `devDependencies` in `package.json` making sure to specify the version as `next` and update your `svelte.config.cjs` to [specify your chosen adapter](https://kit.svelte.dev/docs#configuration-adapter). The following official adapters are available:

- [@sveltejs/adapter-node](https://github.com/sveltejs/kit/tree/master/packages/adapter-node)
- [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static)
- [@sveltejs/adapter-netlify](https://github.com/sveltejs/kit/tree/master/packages/adapter-netlify)
- [@sveltejs/adapter-vercel](https://github.com/sveltejs/kit/tree/master/packages/adapter-vercel)
- ...more soon

[See the adapter documentation for more detail](https://kit.svelte.dev/docs#adapters)
