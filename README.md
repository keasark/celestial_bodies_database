# celestial_bodies_database
This project uses PostgreSQL to create a database of celestial bodies. 
It has 1 main database named "universe". 
The universe database includes 5 tables which are galaxy, star, planet, moon and sun. 

The tables need to satisfy these restrictions:
1. Each table should have a primary key
2. Each primary key should automatically increment
3. Each table should have a name column
4. You should use the INT data type for at least two columns that are not a primary or foreign key
5. You should use the NUMERIC data type at least once
6. You should use the TEXT data type at least once
7. You should use the BOOLEAN data type on at least two columns
8. Each "star" should have a foreign key that references one of the rows in galaxy
9. Each "planet" should have a foreign key that references one of the rows in star
10. Each "moon" should have a foreign key that references one of the rows in planet
11. Your database should have at least five tables
12. Each table should have at least three rows
13. The galaxy and star tables should each have at least six rows
14. The planet table should have at least 12 rows
15. The moon table should have at least 20 rows
16. Each table should have at least three columns
17. The galaxy, star, planet, and moon tables should each have at least five columns
18. At least two columns per table should not accept NULL values
19. At least one column from each table should be required to be UNIQUE
20. All columns named name should be of type VARCHAR
21. Each primary key column should follow the naming convention table_name_id. For example, 
the moon table should have a primary key column named moon_id
22. Each foreign key column should have the same name as the column it is referencing

*All the information is followed by the information on Google Search.
