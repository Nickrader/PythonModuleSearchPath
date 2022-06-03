# PythonModuleSearchPath
Illustration of the Python module search path regarding Keras basics tutorial in Tensorflow

Going through the Keras: Basics tutorials, I had some problems.  https://www.tensorflow.org/tutorials/keras/classification

But the most mysterious of 
all went by many names.
The culprit was how Python finds and imports modules.
I was enthusiastic with joy at the discovery and continued to clarify to myself what was happening.

This is that exercise. 

TL;DR:  Don't name your .py file the same as an import.  This is why some errors are 'magically' fixed by changing the name of your python file.
