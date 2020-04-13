Porous Structure
**********************************

.. note:: Geometry setup of porous structure refers to obstacles configuration.  

The RANS equations for fluid-porous structure interaction

.. image:: image/porous_equation.png
   :align: center

.. note:: In the model, we need to specify :math:`D_{50}, n, \alpha_p, \beta_p, \gamma_p` 

.. code:: ruby
   
   $porous material information$
   1              =npor
   1             = nportype
   0.42,0.4,200.,1.1,0.34 =d50(n), xporosity(n),xalpha(n),xbeta(n),xgamma(n)
   4                   = nporous(n-1)
   0,-0,0,1
   0,0.0,1
   0,1,0,0
   0,-490,0
   0,-1,0,0
   0,525,0
   0,-0,0,1
   0,3.3,0
   $end

The third line: :math:`D_{50}, n, \alpha_p, \beta_p, \gamma_p`
