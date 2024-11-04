# React project with tailwind - Boilerplate

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,tailwind,vite" />
  </a>
</p>

![GitHub last commit](https://img.shields.io/badge/last%20update-04%20/11%20/2024-red)

# **_Table of contents_**

- [Context](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#context)
- [Template structure](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#template-structure)
  - [Structuring the various `src` folder](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#structuring-the-various-src-folder)
  - [Adding `meta-tags` to the project](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#how-to-use-it)
  - [Description of `package.json` scripts](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#how-to-use-it)
- [How to use it](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#how-to-use-it)
- [Technologies used in the template](https://github.com/CalcagnoLoic/react-tailwind-boilerplate?tab=readme-ov-file#technologies-used-in-the-template)

# Context

This template provides a minimal setup to get React Project. It lets you quickly get started on a React project with tailwind and Vitest for unit testing. A CI starter is also included in the template.

# Template structure

This template has a fairly common structure, with a folder for CICD workflows, a public folder and a source folder. A few rules from the linter are used to add a working environment to Typescript.

## Structuring the various `src` folder

In the `src` folder, you can find various subfolders. These are all created in the same way. Namely, a subfolder with a descriptive name and an `index.tsx`. In the template, you'll find them under the name `Example...tsx`. Feel free to rename them or simply delete them to work with something other than `index.tsx`.

What's more, a subfolder can itself have several subfolders. For example, the `User` component can be made up of `UserProfile`, `UserInformation`, `UserImg`, each with its own `index.tsx`.

Let's have a look at the different files:

- `components`: folder containing all application components
- `container`: folder containing the application's container(s)
- `hooks`: folder containing the various custom hooks
- `icons`: folder containing the project's icons in svg code form. Sub-folders for icon families such as `GeneralIcons`, `MediaIcons`, etc. are also possible.
- `layout`: folder containing the project's layout(s), such as grids
- `pages`: folder containing the page(s), whether a SPA or not
- `typographies`: folder containing typographic components for title levels and paragraphs
- `utils`: folder containing utility functions and their associated spec files

Please note that in the `Typographies` folder, as these components are generic, they are already fully written. Modify the `Headings` component if your title levels go beyond `h3`.

## Adding `meta-tags` to the project

In the `index.html` file, meta tags for author, description and keywords are already available. Feel free to modify them!

## Description of `package.json` scripts

Various scripts are already available in the package.json file, but don't hesitate to add your own if you have others!

Here are those already available:

- `dev`: Simply launch the local development server on port 5173
- `dev:compile`: Compiles typescript files in real time (thanks to the --watch flag) during dev phases to ensure that changes don't affect the linter.
- `dev:format`: just formats files (<kbd>ctrl</kbd>+<kbd>s</kbd> works just as well with the prettier file)
- `build`: quick command to send the project to production
- `lint`: the project linter
- `test`: vitest command to launch unit test suites

# How to use it

To use this template, click on `Use this template > Create a new repository`.

Once you've done this, you'll be taken to the standard interface for creating a project, this time using the present template as a base.

Next, the classic steps:

```bash
$ git clone
$ cd path/to/our/project
$ npm i
$ npm run dev
```

And.... happy codings!! 🥳

# Technologies used in the template

- Workflows CICD
- React | v.18.3
- TailwindCSS | v.3.4
- TypeScript | v.5.6
- Vite | v.5.4
- Vitest | v.2.1

---

If you have a modification or see a bug, don't hesitate to open a pull request 😊
