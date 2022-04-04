# CIDM6330-project
Project repository for CIDM6330 Spring 2022 Project.

Final shooters log project for CIDM 6330 Software Development class. West Texas A&M University Spring 2022.

Author: Robert Stockwell

## Abstract

This is to build a working site for following *Test Driven Development* (TDD) method of building software. Following the method ologies in the APP book. Using Flask as a processor and SQLAlchemy for persistance. 

## Structure

1. Domain-Training-Log.drawio - This is the domain model that was initially worked up for the project. Created using the Draw.io desktop software.
    * Working on modifying as we move along the process.
    * Updated using the APP reference in Chapter 6 Unit of Work figure 6-1. (Don't know if it right or not)
2. Domain-Training-Log.pdf - export of the latest drawio file
3. athletes (folder) - storage location for all of the athlete based functions
4. goals (folder) - storage location for all of the goal related functions. 
5. service (folder) - this is where the main application will live. Does this follow the service layer methodology? 
6. tests (folder) - holds all of the test scripts for checking the application. 
7. shooterlog.py - main entry into the program.


## Notes

- Building with testing in mind initially, I'm starting with the athlete part of the project. I'll then look a the Goals and Drills pieces. Using Barky app and other code from the class as a baseline for how to make my *Shooters Log* work and build it up on the TDD 
- I know this is not as far along as it should be. I'm continually working on getting this under my belt.
- This is an area of the IT world that I identified that I was not good at a long time ago and why I'm concentrating on the leadership and project management side of things.


## Helpful links (for me)

- General Tutorials / Software
    * [Awesome Software Architecture](https://awesome-architecture.com/)
    * [Draw.io](https://app.diagrams.net/)
    * [Mark Down Guide](https://www.markdownguide.org/)
- Python
    * [Learn Flask for Python - FreeCodeCamp on YouTube](https://www.youtube.com/watch?v=Z1RJmh_OqeA)
    * [Python Modules](https://realpython.com/python-modules-packages/)
- Unit of Work
    * [SQLAlchemy and The Unit of Work Pattern](https://medium.com/craftsmenltd/sqlalchemy-and-the-unit-of-work-pattern-dfa91a098023)
    * [Repository And Unit Of Work Pattern In Python](https://io.made.com/blog/2017-09-08-repository-and-unit-of-work-pattern-in-python.html)