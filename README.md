# PostgreSQL
## Prerequisites
### https://www.datacamp.com/courses/intermediate-sql
## Courses
### https://www.datacamp.com/courses/cleaning-data-in-postgresql-databases?utm_medium=email&utm_source=customerio&utm_id=5798169&utm_campaign=dc_insights&utm_term=regnewcourse
## Notes
```
psql postpresql://user@pass:server/database 
COPY TABLE_NAME
FROM 'TABLE_NAME.csv'
DELIMETER ','
CSV HEADER;
-- COMPARE WHERE consider with NULL
WHERE FIELD_A != '1' OR FIELD_A IS NULL
-- TRANSACTION
BEGIN TRANSACTION_A;
-- INSERT ...
-- UPDATE ...
-- DELETE ...
COMMIT;
-- SELECT ...
```
