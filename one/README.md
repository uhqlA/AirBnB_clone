AirBnB project.

Python Packages A Python file can be a module but when this file is in a folder, we call this folder a package.

File organization is really important in a big project. This means for Python: packages everywhere.

Web static learn HTML/CSS create the HTML of your application create template of each object

MySQL storage replace the file storage by a Database storage map your models to a table in database by using an O.R.M.

Web framework - templating create your first web server in Python make your static HTML file dynamic by using objects stored in a file or database

RESTful API expose all your objects stored via a JSON web interface manipulate your objects via a RESTful API

Web dynamic learn JQuery load objects from the client side by using your own RESTful API

Storage Persistency is really important for a web application. It means: every time your program is executed, it starts with all objects previously created from another execution. Without persistency, all the work done in a previous execution won’t be saved and will be gone.

In this project, you will manipulate 2 types of storage: file and database. For the moment, you will focus on file.

Why separate “storage management” from “model”? It’s to make your models modular and independent. With this architecture, you can easily replace your storage system without re-coding everything everywhere.

You will always use class attributes for any object. Why not instance attributes? For 3 reasons:

Provide easy class description: everybody will be able to see quickly what a model should contain (which attributes, etc…) Provide default value of any attribute In the future, provide the same model behavior for file storage or database storage
