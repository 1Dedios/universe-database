# Universe Database

Tables in the Database:
- planet
- moon
- star
- galaxy
- locate_people


Foreign Keys in the Database:
- planet->star
- star->galaxy
- moon->planet

Rebuild Database:
- cd into dir with the universe.sql file
- run the following command on terminal: $ psql -U postgres < universe.sql
