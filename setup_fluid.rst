Fluid Parameters
**********************************

.. code:: ruby
   
   $fldparam
   1.0e-06,-0.0,-9.8,0.,0.0,1000.  = xnu,gx,gy,ui,vi,rhof
   $end

* XNU:(>0.0, ∼1.0e-06) Fluid kinematic viscosity. * GX: (∼0.0) Gravity acceleration in the positive x direction.* GY: (∼ -9.81) Gravity acceleration in the positive y (z) direction.* UI: (∼0.0) Initial fluid velocity in the positive x  direction. 
* VI: (∼0.0) Initial fluid velocity in the positive y  direction
* RHOF: (>0.0, ∼1.0) Fluid density in the F = 1.0 regions. RHOF is a relative value, 1.0 value can be used for fresh water. Pressure and forces results will be scaled according to RHOF.
