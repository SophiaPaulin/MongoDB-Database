1. Find all the information about each products

SELECT *
FROM products;

2. Find the product price which are between 400 to 800

SELECT *
FROM product 
WHERE price BETWEEN 400 TO 800;

3. Find the product price which are not between 400 to 600

SELECT *
FROM product 
WHERE price NOT BETWEEN 400 TO 600;


4. List the four products which are grater than 500 in price

SELECT *
FROM product 
WHERE price GREATER THAN 500;


5. Fine the product name and product metirial of each products

SELECT product name, product metirial 
FROM products ;

6. Find the product with a row id of 10

SELECT *
FROM product 
WHERE Id = 10;


7. Find only the product name and product metirial

SELECT product name, product metirial ;


8. Find all the product which contain the value of soft in product metirial

SELECT *, VALUE(soft)
FROM products 
GROUP BY product metirial ;


9. Find products which contain product color Indigo and product price 492.00

SELECT *
FROM products
WHERE colour, price LIKE "Indigo, 492.00";

10. DELETE the products which product price value are 28

DELETE FROM products 
WHERE product price < 28;