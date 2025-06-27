# Grazioso Salvare Dashboard

- How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

There are several design choices that I make in order to ensure the programs I produce are maintainable, readable, and adatable.
For example, the CRUD module I developed exposed a Python class that was flexible and generic enough to accept different
arguments depending on which database and collection the user wanted to interact with.
Each of the methods had simple names that clearly conveyed their intent. I also made sure each method had a descriptive
docstring and inline comments which clearly communicated the funcionality of the code.
By creating all of this in a stand-alone python file, it leaves open the possibility of adapting it separaetly from the
dasboard code to avoid tight coupling between the back-end and front-end code.
By implementing the module in such a manner, it allows the code to be leveraged by a variety of components, whether they
be dashboards, APIs, or CLI tools.

- How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

As a computer scientist, I

- What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
