# SQL-Scripts
This is a repo that contains a quick start for SQL beginners

### ORDER OF STUDY
1. **basicFunctions.txt** - start by creating a database and using it
2. **creatingCompanyDatabase.txt** - creates *tables* for a company such as employee, branch and client etc
3. **basicQueries.txt** - these are the basic queries you can run
4. **functions.txt** - shows the use of functions such as COUNT, AVG, SUM
5. **joins.txt** - uses **join** to connect two tables using columns
6. **union.txt** - joins tables using rows
7. **nestedQueries.txt** - these are subqueries within the queries
8. **wildcards.txt** - considers wildcards such as LIKE
9. **triggers.txt** - creates triggers before insertion are made or tables undergo altering

## New Lessons
Instead of installing mysql as a server, just install docker desktop and then manage all applications as containers.
It is easier to run mysql once docker desktop is installed:
1. docker pull mysql
2. docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=<password> -d mysql
3. docker exec -it some-mysql mysql -uroot -p

Now create your database and tables. 
