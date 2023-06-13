# Fullstack Authentication Example with Next.js and NextAuth.js

This is the starter project for the fullstack tutorial with Next.js and Prisma. You can find the final version of this project in the [`final`](https://github.com/prisma/blogr-nextjs-prisma/tree/final) branch of this repo.

## CLI Lists:

* `npx prisma migrate dev` or `prisma db push` - update DB schema, migrate table to DB, and regenerate prisma client
* `npx prisma migrate dev --name update_folder_migration_name` - generate sql migration into folder `update_folder_migration_name`
* `npx prisma generate` - regenerate Prisma Client
* `npx prisma migrate status` - check DB migration status with schema
* `npx prisma studio` - open Prisma studio DB GUI