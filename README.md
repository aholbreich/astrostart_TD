# Astro + TailwindCSS project stater

A minimalistic Astro project starter. Using Astro 5, Tailwind 4. It also includes Apline JS.

## Usage

Bootstap new project using this template

```bash
pnpm create astro@latest --template aholbreich/astro_start_tailwind
```

Alternative clone this repo and just start coding. The following commands should help

### Commands

All commands are run from the root of the project, from a terminal:
I'm in favor of `pnpm` but `npm` and yarn would work as well.

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `pnpm install`          | Installs dependencies                            |
| `pnpm dev`              | Starts local dev server at `localhost:3000`      |
| `pnpm build`            | Build your production site to `./dist/`          |
| `pnpm preview`          | Preview your build locally, before deploying     |
| `pnpm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro --help` | Get help using the Astro CLI                     |

if preview is not working, you can workaround whith:

```
pnpm build
pnpm dlx serve dist
```

## Includes

* Astro 5.3
* Astro Icon
* Astro SEO
* Astro MDX
* Tailwindcss 4
* Alpinejs
* Netlify

