Numerical Parameters
**********************************

.. code:: ruby
   
   $numparam
   0.01,150,0.5,0.05,1.0          = delt,twfin,prtdt,sfdt,utot
   6,3,1,1   = kl,kr,kt,kb
   $end

* DELT: (:math:`>` 0.0, :math:`\sim` 0.005) Initial time step of calculation. Once the calculation begins, DELT can change from its initial value if the automatic time step adjustment flag AUTOT :math:`\ne 0`.
* TWFIN (>0.0) Final simulation time.
* PRTDT: (>0.0) Time step for data writing. If PRTDT > TWFIN, data will not be written.
* AUTOT (set to 1.0) Automatic time step adjustment during the simulation (AUTOT :math:`ne` 0). If AUTOT is equal to 0, the time step is DELT.
* KL, KR, KT, KB Boundary condition flag for the left, right, top and bottom boundaries (L, R, T and B), respectively. 

  #. Rigid Free-Slip
  #. Rigid No-Slip
  #. Continuative Outflow (open)
  #. Periodic
  #. Applied Pressure
  #. Specified Inflow/Outflow 
