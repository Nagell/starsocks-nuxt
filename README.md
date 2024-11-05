# Dawid Nitka - Portfolio

> [!NOTE]
> This project is still in progress.  

It is a personal portfolio website built with:

- Nuxt,
- Tailwind CSS,
- and Supabase.  

Its main goal it to try out a combination of Nuxt and Supabase, ideally in the SSR mode.

## TODO

- [x] Add Supabase integration
- [x] Add Tailwind CSS integration
- [x] Add admin panel with authentication
- [x] Add server-side CRUD operations for projects
- [ ] Add server-side CRUD operations for images
- [ ] Add i18n
- [ ] Create a design
- [ ] Add animations
- [ ] Add meta tags
- [ ] Deploy to Vercel
- [ ] Add Vitest and tests
- [ ] Add CI/CD

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

## Development Server

Start the development server on <http://localhost:3000>

```bash
npm run dev
```

## Supabase types

To generate types for Supabase, run the following command:

```bash
# Login safely to Supabase
npx supabase login

# Generate types
npm run generate:supabase
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
