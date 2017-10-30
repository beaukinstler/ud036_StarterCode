Movie Trailers
================

This is a sample project for Udacity's "Programming Foundations" cource, and the Full Stack Web Dev nanodegree.
It's a project that uses python to explore the concepts of Object Oriented Programming (OOP), and get a taste programming for the web.
This application statically stores a list of Movie() objects, and using attributes like youtube_trailer, and poster_art, generate a static web page to display them.  It relies on a fork of Udacity's 'fresh_tomatoes.py' module to generate the html page. The HTML page is using Bootstrap and   The orginal source of this can be found [here](https://github.com/udacity/ud036_StarterCode)

As a side function, when the python module is run from a terminal, any movie that shows up on the web page, will also have it's name and description outputed to the terminal.

Getting Started
---------------

You'll need to have Python installed on your computer. Python 2.7 is the version this application is developed on. Python 3.2 may work, but isn't the tested version.

Documentation and Support
-------------------------
This is a demo project, and there is planned support. However, you may find support on the [Udacity forums](https://discussions.udacity.com/).

Usage
-----

1. Download and unzip the files in this [zip file](https://github.com/beaukinstler/ud036_StarterCode/archive/master.zip), or clone with `$ git clone git@github.com:beaukinstler/ud036_StarterCode.git`
1. `cd` into the 'ud036_StarterCode' folder.
1. Edit the "entertainment_center.py" file.
    * The movies can be changed in the `make_list_of_movies()` function.
    * NOTE: You must create a Movie() object for each movie that you want to include.
1. Ensure all the movie instances have also been added to the `movies_list` array, if you want them show up on the web page.
1. run the entertainment_center.py file.
    * In most steups, with python installed, you should be able to run this command from the folder with this code
        > `$ python entertainment_center.py`
    * This will run the code, create a `fresh_tomatoes.html` file in the working directory, and launch a web browser to read the file.

Issues
------

Contributing
------------

This is a demo project and will not be actively maintained. Your tallents will be far more useful elseware.

Credits
-------

Beau Kinstler - Developer

Udacity and all it's contributers

License
-------

[MIT License](https://opensource.org/licenses/mit-license)
