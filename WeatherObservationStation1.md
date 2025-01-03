## **Task:**
#### Query a list of CITY and STATE from the STATION table.
#### The STATION table is described as follows:
```sql
CREATE TABLE STATION (
    ID NUMERIC,
    CITY VARCHAR(21),
    STATE VARCHAR(2),
    LAT_N NUMERIC,
    LONG_W NUMERIC
);
```
#### where LAT_N is the northern latitude and LONG_W is the western longitude.
## **Solution:**
```sql
SELECT CITY, STATE FROM STATION;
```
