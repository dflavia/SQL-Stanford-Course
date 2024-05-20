# SQL-Stanford-Course
Practice exercises based on the Stanford course on Relational Databases and SQL on EDX (SOE.YDB-SQL0001)\
All exercises were fulfilled following the constructs supported by SQLite.

**Movie Rating Database:**

Movie ( mID, title, year, director )
There is a movie with ID number mID, a title, a release year, and a director.

Reviewer ( rID, name )
The reviewer with ID number rID has a certain name.

Rating ( rID, mID, stars, ratingDate )
The reviewer rID gave the movie mID a number of stars rating (1-5) on a certain ratingDate.

**Social-Network Database:**

Highschooler ( ID, name, grade )
There is a high school student with unique ID and a given first name in a certain grade.

Friend ( ID1, ID2 )
The student with ID1 is friends with the student with ID2. Friendship is mutual, so if (123, 456) is in the Friend table, so is (456, 123).

Likes ( ID1, ID2 )
The student with ID1 likes the student with ID2. Liking someone is not necessarily mutual, so if (123, 456) is in the Likes table, there is no guarantee that (456, 123) is also present.
