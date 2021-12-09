npm install --save-dev prisma to update

Setup a new Prisma project
yarn prisma init

Generate artifacts (e.g. Prisma Client)
yarn prisma generate

Browse your data
yarn prisma studio

Create migrations from your yarn Prisma schema, apply them to the database, generate artifacts (e.g. yarn Prisma Client)
yarn prisma migrate dev

Pull the schema from an existing database, updating the yarn Prisma schema
yarn prisma db pull

Push the yarn Prisma schema state to the database
yarn prisma db push
