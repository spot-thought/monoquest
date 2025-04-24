# Monoquest: Nx Monorepo + RR7 App + ShadCN 

## Objective
This assessment is designed to evaluate your ability to:

* Set up a modern JavaScript monorepo using Nx
* Create a React Router v7 (RR7) app with modern UI tooling
* Optionally extend Nx with a custom generator

## Task Requirements

### 1. Create an Nx Monorepo with a React Router 7 App
* Set up a new Nx monorepo using modern JavaScript tooling: ESModules, latest TS and strict type checking.
* Organize your workspace with meaningful project and library structure.
* Keep the configuration as DRY as possible.
* Create a RR7 app with the bundler of your choice.
* Use Tailwindcss 4.0 for styles and Shadcn for your component library.

### 2. Implement Nested Routes with Breadcrumbs
* Set up three nested routes: `/foo`, `/foo/bar` and `/foo/bar/baz`.
* The breadcrumb labels for each page (e.g., `First`, `Second`, `Third`) should be dynamically loaded from a client-side source, such as a simulated config or API.
* The initial labels should reflect the depth of the route (e.g., `First`, `Second`, `Third`).
* Include a button on each page that randomizes the breadcrumb labels when clicked.
* Pages should provide a smooth and consistent experience

### 3. Optional: Write an Nx Generator
* Write a custom Nx generator that scaffolds a new RR7 app
* The generated app should match your existing structure and conventions
* Account for any manual setup steps in your generator logic

## Submission Guidelines
* Push your code to a public GitHub repo.
* Include a short README.md with setup instructions and anything you want to call out.
* Bonus points for thoughtful structure, clean code, and usage of best practices.
