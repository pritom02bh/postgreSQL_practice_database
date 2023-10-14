# postgreSQL_practice
My Practice  code and query for PostgreSQL

### CREATE TABLES

    CREATE TABLE customer(
    first_name VARCHAR(30) NOT NULL,
    last_name VARCHAR(30) NOT NULL,
    email VARCHAR(50) NOT NULL,
    company VARCHAR(50) NOT NULL,
    street VARCHAR(50) NOT NULL,
    city VARCHAR(40) NOT NULL,
    state CHAR(2) NOT NULL,
    zip SMALLINT NOT NULL,
    phone VARCHAR (20) NOT NULL,
    birth_date DATE  NOT NULL,
    sex CHAR(1) NOT NULL,
    date_entered TIMESTAMP NOT NULL,
    id SERIAL PRIMARY KEY
    );

### INSERT DATA


