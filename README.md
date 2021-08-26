# Installation libraries

1)pip install neo4j

2)pip install pandas

3)pip install py2neo

# Requirements
Python versions Neo4j versions

The following versions of Python and Neo4j (all editions) are supported:

    Python 2.7 / 3.4 / 3.5 / 3.6 / 3.7 / 3.8 / 3.9
    Neo4j 3.4 / 3.5 / 4.0 / 4.1 / 4.2 / 4.3 (the latest point release of each version is recommended)

Py2neo provides support for the multi-database functionality added in Neo4j 4.0. More about this can be found in the documentation for the Graph class.

If you don't have Neo4j install on your machine then open Neo4j sandbox from https://sandbox.neo4j.com/.
Click on New project and select blank sandbox.
Go into connection details you will get username, password and all other thing that you require to establish connection.


# For establishing connection
graph = Graph("bolt://localhost:7687", user="pass", password="pass")

put your bolt instead of "bolt://localhost:7687"
put your username intead of "pass"
put your password instead of"pass"

# Execution on Neo4j browser
Open neo4j browser from Neo4j database or from sandbox
Write cypher query "MATCH(n) RETURN n" on the top of browser.
On the left side you will get count of nodes and relationships.
