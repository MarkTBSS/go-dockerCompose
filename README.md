```
docker-compose up

go to Container Exec
psql -U root -d postgres 

postgres=#
SELECT usename FROM pg_user;
\l
\c wallet

wallet=#
\d
\dt
select * from user_wallet;

ALTER USER root WITH PASSWORD 'new_password';
```