# postgres-setup-macOS


1. Install PostgreSQL using brew:

   ```brew install postgresql```
2. Restart the service:

   ```brew services restart postgresql```

3. Activate postgres CLI:

    ```psql postgres```
4. Create a user:
   
    ```CREATE ROLE username WITH LOGIN PASSWORD 'password';```
   
     ```ALTER ROLE username CREATEDB;```

5. Exit postgres CLI:

      ```\q```

6. Start a session with the user:

   ```psql postgres -U username```
7. Create a database:
   
   ```CREATE DATABASE database_name;```

8. Connect with the database:

   ```\c database_name```
9. Test by adding a table:

   ```CREATE TABLE profile(id int PRIMARY KEY, name VARCHAR(40));```

10. Check the table list:

   ```\d```

Congrates! you did it.👏😊
   
