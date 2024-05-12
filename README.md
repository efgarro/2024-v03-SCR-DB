## Technologies Used

- Postgres 16.2
- dbdiagram.io / Entity-Relationships Design Tool
- PL/pgSQL - SQL Procedural Language
- psql - PostgreSQL interactive terminal


## psql Commands

```sh
psql --host=localhost --port=5432 --username=postgres --dbname=postgres   [password: efgarro]

psql --host=localhost --port=5432 --username=efgarro --dbname=2024-v03-scr-d   [password: efgarro]

\l list all databases
\c <db-name>   switch to another db
\dt list db tables
\d <table-name> describe a table
\d+ <table-name> more information about a table
\du lists users and their roles
\df lists all functions
\? get all psql commands
\x
\! cls
\q quit
```


## Git Setup

```sh
git init
git add *
git commit -m "0301a"
git branch -M main
git remote add origin https://github.com/efgarro/2024-v03-SCR-DB.git
git push -u origin main
```


## Tags Naming Convention

```sh
schema_type:
wfall
lodge
trail
resta
users

hub:
climon
ptovjo
tmrndo
stacrz
nicoya
lberia
perzel
domcal
jacher

region:
guanac
caribe
zonsur
pactrl
```

