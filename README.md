# nlp2sql
A basic natural language processor to parse queries on relational databases inputted by the user in simple english, and obtain the equivalent SQLquery. 

This project was done as a part of my final high school project. Although the final ideas used to implement the final project wasn't the smartest/ most efficient way to go about things, the ideas I used and the code I wrote are completely my own.

Please refer to the final project report to better understand the source code and how to use the project. (Skip to page 25 of the report to see examples of execution).

Awards/ Recognition: This project won the second best high school project in Computer Science. It was also the first attempt at tackling this project statement within my school.

Learnings from this project:
- Working completely within the constraints of only what was taught in school was a great challenge. This meant that I disallowed myself from using existing libraries for even simple data structures like queues and vectors, and coded them from scratch. It was a good exercise to test my skills in object oriented programming.
- Value of project outlining and planning. Given that there were so many classes involved, and a lot of implementation involved, it was very easy to get lost in the huge mass of code. Sketching out a plan for the order in which to implement different classes, and testing at each step to ensure everything worked fine was a huge learning.
- Value of commenting every section of code and prioritising readability. 

Broad areas to improve:
- Although the source code is well-commented, I didn't partition my code into separate files, and create a proper file system. Instead, the entire source code is in one large cpp file. I intend to clean up this code and create a better more readable file system in the future.
- This project only takes in queries in natural english and gives the SQL equivalent query. It doesn't directly connect to an SQL database and run the query in the backend. This is a useful feature I intend to add to the project in the future.




