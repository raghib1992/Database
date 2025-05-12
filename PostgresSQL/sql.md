## Select

SELECT column_name FROM table name;

SELECT column_1, column_2 FROM table name;

## Distinct
#### To remove duplicates values in column

SELECT DISTINCT(column) FROM table_name; 

SELECT film_id, title FROM film;

SELECT * FROM film;

SELECT * FROM customer;
 
SELECT first_name, last_name, email FROM customer;

SELECT DISTINCT(release_year) FROM film;

SELECT DISTINCT(rental_rate) FROM film;

SELECT DISTINCT(rating) FROM film;
