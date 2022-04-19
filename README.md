# Todo_application Guide

# Create a Database and Database User

1 - sudo su - postgres

2 - psql

3 - CREATE DATABASE todo_project;

4 - CREATE USER myuser WITH PASSWORD 'password';

5 - ALTER ROLE myuser SET client_encoding TO 'utf8';

6 - ALTER ROLE myuser SET default_transaction_isolation TO 'read committed';

7 - ALTER ROLE myuser SET timezone TO 'UTC';

8 - GRANT ALL PRIVILEGES ON DATABASE todo_project TO myuser;

9 - \q

10 - exit


# Prerequisites

1 - you need to install python 3.8

2 - postgres db
