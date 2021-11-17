### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
> 	Object relationnal database(ORDBMS)
> 	Powerful and popular
> 	Follows SQL standard closely

- What is the difference between SQL and PostgreSQL?
> 	It is not important, according to Colt's note. read at wiki if you are curious. 

- In `psql`, how do you connect to a database?
> 	psql < my_databasename.sql

- What is the difference between `HAVING` and `WHERE`?
> 	Having is to determine which grouped results to keep
> 	Where is to decide which role to use

- What is the difference between an `INNER` and `OUTER` join?
> 	The major difference between inner and outer joins is that inner joins result in the intersection of two tables, whereas outer joins result in the union of two tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
> 	in a left outer join, all rows from the left table will be returned plus the rows that the right table had in common. In contrast, for a right outer join, all rows from the right table will be returned plus the rows that the left table had in common.

- What is an ORM? What do they do?
	ORM means Object Relational Mapping. It translates between OOP in our server language and relational data in database. Can use by itself or with other web framworks. ( for example < SQLAlchemy)

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
>   -Need to review 

- What is CSRF? What is the purpose of the CSRF token?
> 	A CSRF Token is a secret, unique and unpredictable value a server-side application generates in order to protect CSRF vulnerable resources. 
> 
> The tokens are generated and submitted by the server-side application in a subsequent HTTP request made by the client.
> 
> After the request is made, the server side application compares the two tokens found in the user session and in the request. If the token is missing or does not match the value within the user session, the request is rejected, the user session terminated and the event logged as a potential CSRF attack.
> read more at [[https://www.neuralegion.com/blog/csrf-token/]](https://www.neuralegion.com/blog/csrf-token/)

- What is the purpose of `form.hidden_tag()`?
`The form. hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks. All you need to do to have the form protected is include this hidden field and have the SECRET_KEY variable defined in the Flask configuration.`
