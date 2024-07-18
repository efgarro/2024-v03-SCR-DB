## Technologies Used

- Postgres 16.2
- dbdiagram.io / Entity-Relationships Design Tool
- PL/pgSQL - SQL Procedural Language
- psql - PostgreSQL interactive terminal

## psql Commands

```sh
psql --host=localhost --port=5432 --username=postgres --dbname=postgres   [password: efgarro]

psql --host=100.26.47.1 --port=5432 --username=efgarro --dbname=2024-v10-scr-db   [password: efgarro]

psql --host=100.26.47.1 --port=5432 --username=postgres --dbname=template1 [AWS EC Instance]

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

## Connectiong to EC2 Instance


```sh
ssh -i "learn-linux.pem" ubuntu@ec2-100-26-47-1.compute-1.amazonaws.com
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
hubxx
rgion

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

## AWS Postgres Server

https://ubuntu.com/server/docs/install-and-configure-postgresql
https://medium.com/@pantaanish/setting-up-postgresql-on-an-ec2-instance-a-step-by-step-guide-9be2e3348fdb

```sh
ssh -i "learn-linux.pem" ubuntu@ec2-100-26-47-1.compute-1.amazonaws.com
psql --host=100.26.47.1 --port=5432 --username=postgres --dbname=postgres [AWS EC Instance]
```

## pg_uuidv7 Extension

https://pgxn.org/dist/pg_uuidv7/#build

```sql
SELECT uuid_generate_v7();

           uuid_generate_v7           
--------------------------------------
 018570bb-4a7d-7c7e-8df4-6d47afd8c8fc
(1 row)
```