# lipid21

Lipid21 parameters as described in:

Dickson, C.J., Walker, R.C., Gould, I.R. Lipid21: Complex Lipid Membrane Simulations with AMBER, Submitted, 2021.

Inside "lipid21" you will find:
- leaprc.lipid21
- lipid21.dat
- lipid21.lib

To install, run the following:
- cp leaprc.lipid21 $AMBERHOME/dat/leap/cmd/
- cp lipid21.dat    $AMBERHOME/dat/leap/parm/
- cp lipid21.lib    $AMBERHOME/dat/leap/lib/

For each lipid type validated, you will find a folder containing:
- input_LIPID_128.pdb (relaxed box ready for tleap)
- build.leap          (input file to build topology with tleap)
- start.rst           (relaxed box in Amber restart format)

There is also "prod.in" used for 300 ns production simulations.
Temperature is set to 303 K - update for your lipid type.

