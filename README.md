# Prototyping in code

This is an attempt to create a simple framework for simple prototypes in code. The objective is to allow designers with limited knowledge of HTML and CSS to create a low-fidelity wireframe, using code instead of Axure, Balsamiq or Photoshop. 

# What do you need

Realistically, a text editor and a browser. But I would recommend you to use at least SASS. It's very simple to learn from CSS and will keep your prototypes a lot cleaner. 

The simple way to start using SASS is with the [Scout App](http://mhs.github.io/scout-app/).


If you're using a mac, I recommend you to use a webserver. Simply open a terminal window, navigate to the directory you're saving your files, and type:

python -m SimpleHTTPServer 8000


# How to use it

Grid documentation to be added. Check the code for examples.

Some basic styling can be added using the following classes:

.lowbox  // 1px #ccc border box, no background, for low-fidelity wireframes
.centerise // make it centre aligned, both horizontal and vertical
.background-low // Solid #f2f3f4 background box
.background-mid  // Solid #ccc background box 
.height100 // 100px height
.height150
.height200
.height300
.height400
