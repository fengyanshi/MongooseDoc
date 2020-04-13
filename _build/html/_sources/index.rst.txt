.. Mongoose documentation master file, created by
   sphinx-quickstart on Sun Apr 05 13:22:32 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. image:: image/bubbles.jpg

The development of MONGOOSE is based on the RIPPLE code for incompressible Navier-Stokes equations. The RIPPLE code is extended to include multiple porous media layers, air bubbles, suspended sediment, as well as a more complex solid geometry representation than is available in RIPPLE. Reynolds averaging is performed, and two turbulence closure options are provided. 

.. image:: image/wave_structure.png
   :width: 500px
   :height: 250px
   :align: right

The code and test cases are available at `the github site  <https://github.com/fengyanshi/MongooseDoc>`_. Test cases include wave propagation, flow through porous structures, wave interaction with a caisson breakwater, wave shoaling and breaking on a beach and wave--induced sediment transport and air bubbles are provided.

This site serves as the ONLINE DOCUMENTATION of MONGOOSE. Detailed development and applications of the model can be found in Shi et al.(2004), Misra et al. (2006) and Shi et al. (2010).  

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   intro
   compile
   setup
   post
   examples

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
