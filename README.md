## Add Files to Connect Two Databases Locally

You will need to create two .env files for your project: .env.test and .env.development. Into each, add PGDATABASE=<database_name_here>, with the correct database name for that environment (see /db/setup.sql for the database names). Double check that these .env files are .gitignored.

.env.development (in here write PGDATABASE=nc_news)
.env.test (in here write PGDATABASE=nc_news_test)
