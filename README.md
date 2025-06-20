# MaPFlex (MaPFlow + FEM)

The code is developed as a strongly coupled hydro(aero)elastic solver on top of the CFD
code MaPFlow [1](http://dx.doi.org/10.12681/eadd/39271), [2](http://dx.doi.org/10.12681/eadd/46180), [3](http://dx.doi.org/10.12681/eadd/55809).


## TODO

### Initial targets

#### FEM Part

[ ] Create a beam element validated against analytical solutions (iso-static and hyper-static beams) for distributed loads.
[ ] Couple the beam element with PreCICE to plan for coupling with MaPFlow
[ ] Test the coupling by validating the same beam element for a distributed load "calculated" in a fortran code.


#### CFD Part

[ ] Create a PreCICE adapter for MaPFlow
[ ] Couple the Structural with the Fluids part
[ ] Validate for a beam subject to a hydrostatic load (Uinf = 0)
[ ] Validate for a cantilever beam subject to a flow with arbitrary Uinf

### long term targets

TBD

