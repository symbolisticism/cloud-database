# Overview

I wanted to learn how cloud databases work, and I wanted to create my own implementation of one. Having never used NoSQL before, this was a completely new experience for me. I know that cloud databases are a large part of many systems nowadays, so I wanted to get my foot in the door and learn something about them. I know that this experience will provide to be a valuable skill in the future.

I wrote a program that interacts with a populated cloud database. The program connects to a database and it gives the user options for interacting with the database. It allows the user to add a new item to the database, add quantity to an existing item, use quantity from an existing item, and search the inventory of the database. It is a very input/output driven program with a lot of built-in hard-coded functionality.

I wrote this software, as mentioned above, to learn about how cloud databases work and to gain experience so that I can use it in future endeavors. I am interested in working with databases in the future, and I know that cloud databases are heavily used.

[Software Demo Video](https://www.youtube.com/watch?v=lDwlC47trCg)

# Cloud Database

I used Firebase from Google to create a cloud database. It is a NoSQL database, which means it is not structured like a traditional relational database. Instead of rows, columns, primary keys, and foreign keys you have collections, documents, and fields.

As described before, this is a NoSQL database, which means it is not structured like a traditional relational database. 

# Development Environment

I used the Firebase web application for the cloud database and I used VS Code and Python for the development of the software that drives the cloud database manipulation.

# Useful Websites

* [freeCodeCamp]([http://url.link.goes.here](https://www.freecodecamp.org/news/how-to-get-started-with-firebase-using-python/))
* [Medium]([http://url.link.goes.here](https://medium.com/theleanprogrammer/connecting-firebase-6102ef4eca08))

# Future Work

* This could be expanded so that there are multiple "tables" to be queried
* More notifications can be added to it for logging interactions and notifying the user of important events
* More code could be added so that the user could specify which cloud database platform is hosting their database, and the Python script could have the ability to automatically connect to the platform of their choice with the correct information
