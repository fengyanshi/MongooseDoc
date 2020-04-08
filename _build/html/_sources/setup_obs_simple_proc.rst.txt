Procedure
*************************************

.. image:: image/beach.jpg
   :width: 250px
   :height: 200px
   :align: right

You can generate structures one by one and then combine them together. 

* create a file including (x,y) of a quadrangle, which is part of the structure. The file name is *input_structure.txt*

.. code:: ruby
  
  150.0 0.0
  190.0 8.0
  220.0 10.0
  220 0.0

The two columns are (x,y) in meters, raws are points 1 -- 4.

* run matlab script *get_structure.m* to get output file *output_structure.txt*

.. code:: ruby

  3
  0,-0.066667,0,1
  0,4.6667,1
  0,0.2,0,-1
  0,-30,0
  0,-1,0,0
  0,220,0  

* repeat the procedure to get more quatrangles. Note: you should change file names *input_strucuture.txt* and *output_structure.txt*, or run the program in a different folder, to avoid erasing the existing files generated. 
* copy/paste those numbers in *output_structure.txt* to *input*


