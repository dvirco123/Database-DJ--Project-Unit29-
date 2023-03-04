### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL, also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance. It was originally named POSTGRES, referring to its origins as a successor to the Ingres database developed at the University of California, Berkeley. 

- What is the difference between SQL and PostgreSQL?
PostgreSQL trumps SQL Server in several scenarios. Not only is it open-source and free, but it also has several features that are easily available and can be implemented automatically, unlike 
Microsoft SQL Server. Moreover, PostgreSQL has a more suitable concurrency management system

- In `psql`, how do you connect to a database?
In order to connect to a database you need to know the name of your target database, the host name and port number of the server, and what user name you want to connect as. psql can be told about those parameters via command line options, namely -d, -h, -p, and -U respectively.

- What is the difference between `HAVING` and `WHERE`?
A HAVING clause is like a WHERE clause, but applies only to groups as a whole (that is, to the rows in the result set representing groups), whereas the WHERE clause applies to individual rows

- What is the difference between an `INNER` and `OUTER` join?
inner join will keep only the information from both tables that's related to each other (in the resulting table). An Outer Join, on the other hand, will also keep information that is not related to the other table in the resulting tabl

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
A left outer join contains all records of the "left" table even if it has no matches in the "right" table specified in the join. A right outer join contains all records in the "right" able even if it has no matches in the "left" table.

- What is an ORM? What do they do?
Object Relational Mapping
is a technique used in creating a "bridge" between object-oriented programs and, in most cases, relational databases.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
HTTP allows the client to post 'forms' to the server. The server CGI program could use the client's form to change the HTML page sent to the client.

- What is CSRF? What is the purpose of the CSRF token?
Cross-site request forgery
Cross-Site Request Forgery (CSRF) is an attack that forces authenticated users to submit a request to a Web application against which they are currently authenticated.

- What is the purpose of `form.hidden_tag()`?
To generat a hidden field that includes a token that is used to protect the form against CSRF attacks