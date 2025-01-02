<span style="color:red; font-size:38px;">**Task:**</span>

### Query all columns for all American cities in the **CITY** table with populations larger than 100000. The **CountryCode** for America is USA.
### The **CITY** table is described as follows:

```sql
CREATE TABLE CITY (
    ID            SERIAL PRIMARY KEY,
    NAME          VARCHAR(17),
    COUNTRYCODE   VARCHAR(3),
    DISTRICT      VARCHAR(20),
    POPULATION    INT
);
```

<span style="color:red; font-size:38px;">**Solution:**</span>

```sql
SELECT * FROM city WHERE countrycode = 'USA' AND population > 100000
```