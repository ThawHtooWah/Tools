# METABASE
>Metabase is an open source business intelligence tool.

### Download Link
Metabase versions download link with JAR file - [Please Download Here](https://github.com/metabase/metabase/releases/).

### Backup with database (Optional)
- **Create a database for metabase**
- **Using environment variables**  

   Template
   ```sh
   export MB_DB_TYPE=database_type
   export MB_DB_HOST=host_name
   export MB_DB_USER=user_name
   export MB_DB_PASS=user_password
   export MB_DB_DBNAME=database_name
   ```
   Sample 
   ```sh
   export MB_DB_TYPE=mysql
   export MB_DB_HOST=localhost
   export MB_DB_USER=root
   export MB_DB_PASS=root
   export MB_DB_DBNAME=metabase
   ```
### Run Metabase
```java 
java -jar metabase.jar
```