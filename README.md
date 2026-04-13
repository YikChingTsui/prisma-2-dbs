```sh
> npx prisma validate --config=.\db1-prisma.config.ts
Loaded Prisma config from db1-prisma.config.ts.

Prisma schema loaded from prisma\db1-schema.prisma.
The schema at prisma\db1-schema.prisma is valid 🚀

> npx prisma validate --config=.\db2-prisma.config.ts
Loaded Prisma config from db2-prisma.config.ts.

Prisma schema loaded from prisma\db2-schema.prisma.
The schema at prisma\db2-schema.prisma is valid 🚀

> npx prisma db push --config=.\db1-prisma.config.ts
Loaded Prisma config from db1-prisma.config.ts.

Prisma schema loaded from prisma\db1-schema.prisma.
Datasource "db1_db": SQLite database "dev_1.db" at "file:./dev_1.db"

SQLite database dev_1.db created at file:./dev_1.db

Your database is now in sync with your Prisma schema. Done in 242ms

> npx prisma db push --config=.\db2-prisma.config.ts
Loaded Prisma config from db2-prisma.config.ts.

Prisma schema loaded from prisma\db2-schema.prisma.
Datasource "db2_db": SQLite database "dev_2.db" at "file:./dev_2.db"

SQLite database dev_2.db created at file:./dev_2.db

Your database is now in sync with your Prisma schema. Done in 226ms

```