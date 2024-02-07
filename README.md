Apollo Server + GraphQL
## Getting Started

First, run the development server apollo:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:4000](http://localhost:4000) with your browser to see the result.


## GraphQL codegen
Use command `pnpm codegen`, then in folder create `src/graphql` with files `.generated.ts`

```
/* Implement Query.product resolver logic here */
```
Here we will write the code for our product return function.


## Environents
In file .env add information about DB connection
eg.
```
DATABASE_URL="postgresql://postgres:test@127.0.0.1:5432/next14master?mydb?schema=public&serverVersion=16&charset=utf8"
```

## Command prism

```
pnpm prisma migrate dev
pnpm prisma generate
```

![Screenshot](public/images/2024-02-08_00h45_23.png)