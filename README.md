# c0reV2 | Astro + Static CMS

### Configure Static CMS Backend

Navigate to `src/pages/admin.astro` and provide your Git repository details. You can find a list of all supported Git backends at:
<https://www.staticcms.org/docs/backends-overview>


### Install dependencies

```bash
$ npm install
```

### 🛠️ Start Development server

```bash
$ npm run dev
```

If you wish to engage the local backend:

```bash
$ npm run cms-proxy-server
```

Now you can open Static CMS on http://localhost:4321/admin/



## 🛸 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `npm install`              | Installs dependencies                            |
| `npm run dev`              | Starts local dev server at `localhost:4321`      |
| `npm run cms-proxy-server` | Starts Static CMS proxy server for local-backend |
| `npm run build`            | Build your production site to `./dist/`          |
| `npm run preview`          | Preview your build locally, before deploying     |
| `npm run astro ...`        | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help`  | Get help using the Astro CLI                     |


## 👀 Want to learn more about Astro?

Check out [Astro documentation](https://docs.astro.build) or jump into Astro's [Discord server](https://astro.build/chat).

## 📚 Tech Stack

Astro, MDX, Vue, TailwindCSS, Pagefind, Snipcart



