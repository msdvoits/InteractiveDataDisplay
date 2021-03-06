Interactive Data Display
------------------------

Interactive Data Display for JavaScript (IDD for short) is a set of controls for adding interactive visualization of dynamic data to your application. 
It allows to create line graphs, bubble charts, heat maps and other complex 2D plots which are very common in scientific software. 
Dynamic Data Display integrates well with Bing Maps control to show data on a geographic map in latitude/longitude coordinates. 
The controls can also be operated programmatically. 

IDD is being developed in close collaboration between [Information Technologies in Sciences laboratory](http://itis.cs.msu.ru) of Moscow State University 
and Microsoft Research Cambridge. 

Building IDD
------------

In order to build IDD, you need Node.js/npm and git.

Clone a copy of the IDD git repo, enter IDD directory and install development tools packages:

`cd idd`

`npm install`

IDD uses Grunt to run build tasks. You will need to install grunt command line interface as a global package (if not already installed):

`npm install -g grunt-cli`

Now you can build and test IDD by running the grunt command without arguments:

`grunt`

File IDDSamples.html in the root of idd repository contains many samples. Note that some browsers don't run web workers from local file system
for security reasons so some samples may not work if opening IDDSamples.html as local file.

Referencing IDD
---------------

Interactive Data Display is available as Bower package. You can download IDD as bower package by running:

`bower install idd`

Licensing
---------

Please see the file called LICENSE.
