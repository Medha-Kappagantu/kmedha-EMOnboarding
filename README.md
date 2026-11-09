# EM Onboarding Project

This is a Next.js application created for the Engineering Manager onboarding project.

## Prerequisites

Before running this project, make sure you have:

- Node.js version 20.9 or higher (use a version supported by the installed Next.js release)
- npm (Node Package Manager, included with Node.js)
- Git (for cloning and managing the repository)

## Database

This project currently does not use a database, so no local database instance or setup is required.

If a database is added in the future, this section will include instructions for installing, configuring, and starting it locally.

## Installation

1. Clone the GitHub repository:

   ```bash
   git clone https://github.com/Medha-Kappagantu/kmedha-EMOnboarding.git
   ```

2. Navigate into the project directory:

   ```bash
   cd kmedha-EMOnboarding
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

   This command installs the packages listed in `package.json` into the `node_modules` directory.

## Running the Application

Start the development server:

```bash
npm run dev
```

This command starts Next.js in development mode.

Open http://localhost:3000 in your browser to view the application.

You can edit the application by modifying `app/page.tsx`. Changes automatically appear in your browser.

To stop the development server, press `Ctrl + C` in Terminal.

## Production Build

To create an optimized production build:

```bash
npm run build
```

To run the production application after building:

```bash
npm run start
```

## Environment Variables

Environment variables are configuration settings used by an application, such as database connection strings and API keys.

Currently, this project does not require any environment variables.

If environment variables are needed in the future:

1. Create a `.env.local` file in the project root directory.
2. Add the required environment variables and their values.
3. Obtain database credentials from the local database configuration and API keys from the corresponding service provider.
4. Restart the development server after updating the environment variables.

For example, a future application might use:

```env
DATABASE_URL=your_database_connection_string
```

This is only an example and is not currently required.

**Security:** Never commit `.env.local`, passwords, API keys, or other secrets to GitHub.

## Project Structure

- `app/` — Contains the application's pages and layouts.
- `public/` — Contains static assets such as images.
- `package.json` — Defines project dependencies and npm scripts.
- `.gitignore` — Specifies files and directories Git should ignore.
- `README.md` — Provides project setup and usage instructions.

## Learn More

For additional information about Next.js:

- [Next.js Documentation](https://nextjs.org/docs) — Official Next.js documentation.
- [Learn Next.js](https://nextjs.org/learn) — Interactive Next.js tutorial.

## Deployment

The application can be deployed using [Vercel](https://vercel.com/new).

For more information, see the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).