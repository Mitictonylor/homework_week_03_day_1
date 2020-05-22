PostgreSQL practice
Codeclan week3 day1

#SQL Homework
The Springfield Cinema is having a Marvel Movie Marathon! They have asked you to help maintain their database of movies with times and attendees.

To access the database:
First, create a database called ‘marvel’

terminal
createdb marvel
Next, run the provided SQL script to populate your database:

terminal
psql -d marvel -f marvel.sql
Use the supplied data as the source of data to answer the questions. Copy the SQL command you have used to get the answer, and paste it below the question, along with the result they gave.

**Questions**

Return ALL the data in the ‘movies’ table.
Return ONLY the name column from the ‘people’ table
Oops! Someone spelled Krusty The Clown’s name wrong! Change it to reflect the proper spelling (Crusty should be Krusty).
Return ONLY Homer Simpson’s name from the ‘people’ table.
The cinema is showing ‘Batman Begins’, but Batman is DC, not Marvel! Delete the entry from the ‘movies’ table.
We forgot one of the main characters! Add Bart Simpson to the ‘people’ table
Eric Cartman has decided to hijack our movie evening, Remove him from the table of people.
The cinema has just heard that they will be holding an exclusive midnight showing of ‘Avengers: Infinity War’!! Create a new entry in the ‘movies’ table to reflect this.
The cinema would like to make the Iron Man movies a triple billing. Find out the show time of “Iron Man 2” and set the show time of “Iron Man 3” to start two hours later.

**Extension**

Research how to delete multiple entries from your table in a single command.
