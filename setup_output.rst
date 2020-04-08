Output
**********************************

.. code:: ruby
   
   $output format$
   1,0,0        =lout,nanimation,nmean
   6,23.45,45.40,52.73,60.04,70.99,81.97,0,6000,0.1
   $end

An output file is a 2D array with a dimenasion of (imax, jmax). The format is

.. code:: ruby
   
   $output format$
   do j=1,jmax
    write(outputIO,299) (OutputVariable(ij),ij=(j-1)*imax+1,(j-1)*imax+imax)
   end do
   299     format(3x,3000e14.6)
   $end

There are a list of output variables, includeing the fluid function f, velocity (u,v), pressure p, turbulence production rate and turbulent kinetic energy k. The file names list as:

 #. fluid function: data_f.xxxx 
 #. velocity u: data_u.xxxx
 #. velocity v: data_v.xxxx 
 #. pressure: data_p.xxxx 
 #. turbulence production rate: data_prod.xxxx
 #. turbulent kinetic energy: data_k.xxxx 



