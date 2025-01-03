## **Task:**
#### Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
#### The CITY table is described as follows
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
SELECT NAME FROM CITY
WHERE COUNTRYCODE = 'JPN';
```