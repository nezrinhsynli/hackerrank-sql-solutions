## **Task:**
#### Query all columns for a city in CITY with the ID 1661.
#### The CITY table is described as follows:
```sql
CREATE TABLE CITY (
    ID NUMBER PRIMARY KEY,
    NAME VARCHAR2(17),
    COUNTRYCODE VARCHAR2(3),
    DISTRICT VARCHAR2(20),
    POPULATION NUMBER
);
```
## **Solution:**
```sql
SELECT * FROM CITY
WHERE ID = 1661;
```