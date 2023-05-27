## CASE in Sql
```SQL
SELECT name, 
  CASE 
   WHEN genre = 'romance' THEN 'Chill'
   WHEN genre = 'comedy' THEN 'Chill'
   ELSE 'Intense'
  END AS 'genre'
  FROM movies;
  ```
  
Each WHEN tests a condition and the following THEN gives us the string if the condition is true.
The ELSE gives us the string if all the above conditions are false.
The CASE statement must end with END.