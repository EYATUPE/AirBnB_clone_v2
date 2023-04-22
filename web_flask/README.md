Learning flask
0x04. AirBnB clone - Web framework

Resources
Read or watch:

What is a Web Framework?
A Minimal Application
Routing (except “HTTP Methods”)
Rendering Templates
Synopsis
Variables
Comments
Whitespace Control
List of Control Structures (read up to “Call”)
Flask
Jinja

General
What is a Web Framework
How to build a web framework with Flask
How to define routes in Flask
What is a route
How to handle variables in a route
What is a template
How to create a HTML response in Flask by using a template
How to create a dynamic template (loops, conditions…)
How to display in HTML data from a MySQL database



You have a captain's log due before 2023-04-23 (in 1 day)! Log it now!
0x04. AirBnB clone - Web framework
Python
Back-end
Webserver
Flask
 By: Guillaume, CTO at Holberton School
 Weight: 2
 Project will start Apr 20, 2023 6:00 AM, must end by Apr 24, 2023 6:00 AM
 Checker was released at Apr 21, 2023 6:00 AM
 Manual QA review must be done (request it when you are done with the project)
 An auto review will be launched at the deadline
Concepts
For this project, we expect you to look at this concept:

AirBnB clone
Resources
Read or watch:

What is a Web Framework?
A Minimal Application
Routing (except “HTTP Methods”)
Rendering Templates
Synopsis
Variables
Comments
Whitespace Control
List of Control Structures (read up to “Call”)
Flask
Jinja
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is a Web Framework
How to build a web framework with Flask
How to define routes in Flask
What is a route
How to handle variables in a route
What is a template
How to create a HTML response in Flask by using a template
How to create a dynamic template (loops, conditions…)
How to display in HTML data from a MySQL database
sks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.

Tasks
0. Hello Flask!

Write a script that starts a Flask web application:
   * your web appliaction must be listening on 0.0.0.0, port 5000
   * Routes:
       * /:display "Hello HBNB!"
   * You must use the option strict_slashes=False in your route definition

1. HBNB

Write a script that starts a Flask web application:
   * Your web application muist be listening on 0.0.0.0, port 5000
   * Routes:
        * /:display "Hello HBNB!"
        * /hbnb: display "HBNB"
   * You must use the option strict_slashes=False in your route definition

2. C is fun!

Write a script that starts a Flask web application:
   * Your web appliaction must be listeni9ng on 0.0.0.0, port 5000
   * Routes:
       * /display "HBNB"
       * /hbnb:display "HBNB"
       * /c/<text>:display "C" followed by the value of the text variable (replace underscore_symbols with a space)
   *  You must use the option strict_slashes=False in your route definition

3. Python is cool
Write a script that starts a Flask web application:

    * Your web application must be listening on 0.0.0.0, port 5000
    * Routes:
       * /: display “Hello HBNB!”
       * /hbnb: display “HBNB”
       * /c/<text>: display “C ”, followed by the value of the text variable (replace underscore _ symbols with a space )
       * /python/(<text>): display “Python ”, followed by the value of the text variable (replace underscore _ symbols with a space)
            * The default value of text is “is cool”
    * You must use the option strict_slashes=False in your route definition

4. Is it a number?
