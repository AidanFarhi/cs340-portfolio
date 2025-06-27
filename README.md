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

As a computer scientist, I approach each problem at a high level first and then try to break it down into smaller parts.
The Grazioso Salvare requirements were thankfully quite straightforward. I was able to dissect each individual ask into a managanable chunk
of work and eventually combine all of them into the final result. I don't think my approach to this project was much different
than previous assignments. In the future, I would follow a similar approach to develop databases for other projects.
I would break down the requirements and develop a data model that could support them.

- What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

Computer scientists leverage their knowledge of computers to develop products and solve problems. This usually involves
setting up software infrastructure, writing programs, and managing databases and servers, sometimes within a cloud platform.
I would attempt to create data-driven solutions for companies which would allow them to manage their information.
Specifically, dashboards that help users analyze their organization's data.
