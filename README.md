# dezlymacauley.com
_______________________________________________________________________________

**My personal brand website:**

[dezlymacauley.com](https://dezlymacauley.com)

_______________________________________________________________________________

### Technologies Used

| Component            | Technology                |
|----------------------|---------------------------|
| Meta-Framework       | 🏡 SvelteKit, 🧡 Svelte   |
| UI Layout            | 📜 HTML, 💨 Tailwind CSS  |
| Programming Language | 🪄 TypeScript             |
| UI Animations        | 🍀 GSAP                   |
_______________________________________________________________________________

### Maintainance Tasks

1. Review the project structure, 
and ensure that `.gitignore` is setup correctly.
```sh
tree --gitignore -L 4
bat .gitignore 
```

2. Check if websitesite is using the latest version of Deno
```sh
mise latest deno
```

3. Update the Deno version used by the website
```sh
mise use deno@some_specific_version_number
```

4. Scanning for outdated dependencies
```sh
deno outdated
```

5. Updating outdated dependencies
```sh
deno update --latest
```

6. Peform a clean install and build of the project
```sh
deno task setup
```

7. Check that all the links on the website and resume are working
```sh
deno task dev
```
_______________________________________________________________________________
