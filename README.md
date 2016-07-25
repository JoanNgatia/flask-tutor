## Flask Tutorial

### What is Flask?
Flask has been defined as a micro web framework written in Python and based on the Werkzeug toolkit and Jinja2 template engine.That sounds pretty straightforward, but what is a web framework? And what would make flask a micro one?

> A **web framework** is the software framework structure that allows for the development of web applications including web services, resources and APIs.In simpler terms, it is the structure that allows users to , access their facebook page by typing in facebook.com on their browsers.Through this structure, this is referred to as a request, that is sent to a server and a response returned with the requested info, in our case this would be your normal facebook feed.

> A **micro web framework** is thus defined as  a mini web framework since it does not offer all the functionality to be found on full stack web frameworks such as accounts, authentication, input validation and sanitation and database abstraction or object relational mapping.Micro frameworks have little to no dependencies to external libraries.The advantage with this is that the framework is light, has little dependencies to update and allows its users to easily choose what extensions they would like to use in their apps dependent on their needs.A disadvantage is that you have to figure out the dependencies to use by yourself and at times this is difficult since not all projects have awesome user-friendly documentation.

Examples of Python web frameworks are Django, Pyramid and Flask.

__Back to flask…__

In addition to the advantages that come with all microframeworks, flask contains a development server, has integrated support for unit testing, support for secure client side sessions and very extensive documentation.It has two main dependencies:
- Jinja2 Templating engine - Allows for separation of program and presentation logic leaving room for flexibility and easier maintenance of web templates.
- Werkzeug WSGI toolkit - WSGI is a protocol defined to allow communication between python applications and a web server.

### What we’ll be building
A home library management system that
- allows users to register and sign in,
- allows users to add books, edit book titles and delete books from their libraries.
- Users will also be able to mark books as read.

### Flask Installation
Assuming you have pip and virtualenv installed, on your console,

1. Create new environment to isolate our workspace
       `mkvirtualenv flask`
2. Install flask
       `pip install flask`

If you do not have pip or virtualenv installed check out this [doc](http://flask.pocoo.org/docs/0.11/installation/#installation) for instructions.I prefer using virtualenvwrapper to virtualenv.You can check it out [here.](https://virtualenvwrapper.readthedocs.io/en/latest/)
