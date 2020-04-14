This is the directory containing riblet systems used for the proper simulations.

The first one, prism riblet will be based on test_riblet_v5.

The velocity boundary conditions have been modified so that it now has lid-driven, or couette flow.

Hopefully this means we can reduce the inlet length, so I've changed it from 2000 to 500.

Also changed the phase names from water -> biofilm and air -> fluid. Hopefully this should be somewhat less confusing.
///////////////////////////////////////////////////////////////

Currently varying the biofilm thickness and the riblet separation. Current riblet separations are 23, 46 and 92 microns.

Biofilm thicknesses are:

thick = 60 microns
thin = 21 microns
level = 42 microns
//////////////////////////////////////////////
Gravity was still turned on, I've turned it off now, see if it changes anything.
