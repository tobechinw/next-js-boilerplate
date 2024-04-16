# NextJS Boilerplate

Basic NextJS Boilerplate with Next-auth, Drizzle ORM with Postgres and ShadCN with light/dark mode

## Features

- Light/dark mode toggle
- NextAuth with Google OAuth
- Postgres Database
- Drizzle ORM

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATABASE_URL`

`GOOGLE_CLIENT_ID`

`GOOGLE_CLIENT_SECRET`

You will also need to change:

- The postgres password and container name in the docker compose accordingly
- The name of the project in the `package.json` and `package-lock.json` files

## Installation

```bash
  git clone [GIT_REPO_URL]
  cd REPO
  npm install
  touch .env
  docker compose up
  npm run db:push (to run migration on database)
  npm run drizzle (to open up drizzle studio console)
  npm run dev (to launch app)
```

## Acknowledgements

- [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
