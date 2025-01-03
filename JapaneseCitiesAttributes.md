## **Task:**
#### Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.
#### The CITY table is described as follows:
```sql
CREATE TABLE CITY (
    ID SERIAL PRIMARY KEY,
    NAME VARCHAR(17),
    COUNTRYCODE VARCHAR(3),
    DISTRICT VARCHAR(20),
    POPULATION NUMERIC
);
```
## **Solution:**
```sql
SELECT * FROM CITY
WHERE COUNTRYCODE = 'JPN';
```