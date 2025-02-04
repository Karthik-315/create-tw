<img width="1205" alt="image" src="https://user-images.githubusercontent.com/6149523/189049049-36882abb-5a97-460a-929b-cb19b7178153.png">

# Create Tailwind (create-tw)
### The easiest way to get started with TailwindCSS.

It uses popular scaffolding scripts like `create-next-app`, `create-vite`, `create-astro`, or `create-svelte` to scaffold projects and then configures TailwindCSS to work with your project out of the box.

#### npx
```bash
npx create-tw@latest

# OR

npx create-tw@latest <project-name> --template <id>
```
#### yarn
```bash
yarn create tw

# OR

yearn create tw <project-name> --template <id> 
```

#### pnpm
```bash
pnpm create tw

# OR

pnpm create tw <project-name> --template <id> 
```
1. Pick project type
    - Nextjs (create-next-app)
    - Vanilla (create-vite)
    - React (create-vite)
    - Vue (create-vite)
    - Astro (create-astro)
    - Svelte (create-svelte)
    - Preact (create-vite)
    - Solid (degit)
2. Pick language
    - TypeScript
    - JavaScript
3. Pick dependencies
    - Prettier, clsx, etc.
4. Pick Plugins
    - Daisy UI, @tailwindcss/typography, etc
  
It's ready! ✅


### Currently in very early stage of development
Ideas, suggestions and bug reports are much appreciated.
In the following days I'm planning to add support for React, Vue & Svelte with Vite. 



### Scaffolding tools

|id        | Template   | Tool            |
|:---------|:-----------|:----------------|
|nextjs    | Next.js    | create-next-app |
|vanilla   | Vanilla    | create-vite     |
|react     | React      | create-vite     |
|vue       | Vue        | create-vite     |
|astro     | Astro      | create-astro    |
|svelte-kit| Svelte Kit | create-svelte   |
|preact    | Preact     | create-vite     |
|solid    | Solid      | degit           |

NOTE: Add the `-ts` postfix to the ID to install with TypeScript

### Include template id to skip input steps

```bash
npx create-tw@latest --template <id>
# OR
yarn create tw --template <id>
```
