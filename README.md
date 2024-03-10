# Dashboard for Acme in NextJS 14

<img src="./public/hero-desktop.png">

## 🚀 Quick start

```
npm install
npm run dev
```

Your site is now running at `http://localhost:3000`!

## Caveats

- Two files are missing from the repo as they contain sensitive information. The first file is `.env.local` containing the database connection details. Go to the [NextJS database section](https://nextjs.org/learn/dashboard-app/setting-up-your-database) to learn how to set up your own database.
- The second file is `.env` which contains `AUTH_SECRET=your-secret-key` for NextAuth. You can generate a secret key by running `openssl rand -base64 32` in your terminal. Go to the [NextJS authentication section](https://nextjs.org/learn/dashboard-app/adding-authentication) to learn how to set up your own authentication.

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Next.js project.
├── .next
├── app
├── node_modules
├── public
├── scripts
├── .env
├── .env.local
├── .eslintrc.json
├── .gitignore
├── .nvmrc
├── .auth.config.ts
├── .auth.ts
├── middleware.ts
├── next-env.d.ts
├── next.config.js
├── package.json
├── package-lock.json
├── postcss.config.js
├── prettier.config.js
├── README.md
├── tailwind.config.ts
└── tsconfig.json

## 📝 Notes

Here is a live version of the app: [Acme Dashboard](https://nextjs-dashboard-ps.vercel.app)
Use the following credentials to log in:

- Email: `user@nextmail.com`
- Password: `123456`

## 🎓 Learning Next.js

Thanks to Vercel[https://vercel.com] for hosting this project.<br>
Looking for more guidance? Full documentation for Next.js can be found [here](https://nextjs.org/learn).
