###



# Next.js 16 SaaS Boilerplate

Next.js 16 starter for rapidly building SaaS apps with authentication, database, state management, theming, and production-grade DX baked in.



![thumbnail](/public/next.svg)



## Features



- 🚀 Next.js 16 with App Router, React 19, Turbopack enabled
- 🔐 Authentication with Clerk and global route protection middleware
- 🗄️ Prisma ORM with PostgreSQL and Accelerate extension
- 📦 Generated Prisma client under `lib/generated/prisma`
- 🔄 TanStack Query provider with Devtools
- 🎨 Tailwind CSS with extended theme, animations, and dark mode
- 🧹 Biome for linting/formatting; Husky + lint-staged; Commitlint
- 🧪 Strict TypeScript config and path aliases (`@/*`)
- 🧰 Optional local Supabase setup for Postgres + Studio



## Built with



- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Clerk](https://clerk.com/)
- [Prisma](https://prisma.io/)
- [TanStack Query](https://tanstack.com/query/latest)
- [TypeScript](https://www.typescriptlang.org/)
- [Vercel AI Sdk](https://ai-sdk.dev/docs/introduction)


### Tools

- [Biome](https://biomejs.dev/)
- [Husky](https://typicode.github.io/husky/)
- [Commitlint](https://commitlint.js.org/#/)
- [Supabase CLI](https://supabase.com/docs/guides/local-development/cli) (optional)



## Feature Requests



Open a GitHub issue in this repository and describe your request clearly.



### Setting Up Environment Variables



To run the project locally, create a `.env.local` file in the root directory and add the following variables:

```bash
# Database (PostgreSQL)
DATABASE_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Optional Clerk routes if you customize auth pages
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Optional app metadata
NEXT_PUBLIC_APP_NAME=SaaS Boilerplate

# Optional: OpenAI (only if you add AI features)
OPENAI_API_KEY=
```

Optional: If you use Supabase locally, run `supabase start` and point `DATABASE_URL` to the local Postgres connection.



## 📜 License

This project is licensed under the MIT License.



---



Built with ❤️ by [Anayat](https://anayat.xyz)



###
