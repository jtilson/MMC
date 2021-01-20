# MMC
MMC: Molecular Moments Computation.
A Global Arrays parallel code for solving the many body electrostatics problem  
including polarizabilties and hyperpolarizabilitites of arbitrary order. The final
solution can be either a one-step algorithm where the polarizabilities are basically
perturbations, or the full self-consistent iterative solution.

Example use cases: An assembly of molecules and the need to compute interaction energies
for a given ensemble of orientations. This might include, for example, computing Gibbs Ensemble-based gas properties of 
oderate injected natural gas. This is an alternative to the traditional partial-charge based 
methods (such as using a TIP3P style potential) which replaces long range (1/R) explicit charge forces
for the much shorted ranges (1/R^3 and less) in the MMC models.

The code is somewhat dated, however, porting to new machines is rather simple if a port of Global Arrays and MPI
are available.
