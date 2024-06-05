1.1.

a. Crea una base de datos
CREATE DATABASE my_company_database;


CREATE TABLE employees(
 id INT AUTO_INCREMENT,
   birth_date DATE,
   first_name VARCHAR(100),
   last_name VARCHAR(100),
   gender VARCHAR(20),
   register_date DATETIME,
   PRIMARY KEY(id)
 );

b. Columna salario...
mysql> ALTER TABLE employees ADD salary FLOAT;

mysql> ALTER TABLE employees ADD title VARCHAR(20);

mysql> ALTER TABLE employees ADD title_date DATE;

1.2. INSERTAR DATOS.
INSERT INTO employees (birth_date, first_name, last_name, gender, salary, title, title_date, register_date) values ('1981-01-10', 'Sara', 'Wilson', 'female', '10000', 'Ingeniera', '2020-02-02', now()), ('1981-02-10', 'Sara', 'Richards', 'female', '15000', 'Programadora', '2020-01-01', now()), ('1981-03-10', 'John', 'Wayne', 'male', '10000', 'Espía', '2005-01-01', now()), ('1980-09-10', 'Rick 1', 'Sanchez', 'female', '10000', 'Científico', '2020-01-01', now()), ('1980-09-10', 'Rick 2', 'Sanchez', 'female', '10000', 'Astronauta', '2020-01-01', now()), ('1980-09-10', 'Rick 3', 'Sanchez', 'female', '10000', 'Militar', '2020-01-01', now()), ('1980-09-10', 'Rick 4', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 5', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 6', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Sara', 'Watson', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Sara', 'Watson', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 7', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 8', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 9', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 10', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 11', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now()), ('1980-09-10', 'Rick 12', 'Sanchez', 'female', '10000', 'Magisterio', '2020-01-01', now());
