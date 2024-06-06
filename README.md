

# An LES Exploration of the Assumptions used in Retrieving Entrainment from a Mixing Diagram Approach with Ground-Based Remote Sensors

## Group Members
Tessa E. Rosenberger, Thijs Heus, Girish N. Raghunathan, David D. Turner, Timothy J. Wagner,
and Julia Simonson

## Abstract
 A recent study described a method for applying a mixing diagram framework to a convective boundary layer (BL) using ground based observations (Wakefield et al, 2023). In that study, they showed that once they observed the mean BL temperature and water vapor evolution, the surface fluxes, and the large-scale forcing, they could derive the entrainment flux as a residual or closure term. They demonstrated that this approach to estimate entrainment agreed both with an observationally derived water vapor entrainment flux derived from multiple ground based lidars and to large eddy simulation (LES) output. However, entrainment (as used above) is really composed of two terms: the flux of water vapor across the boundary separating the BL from the free troposphere and a second term associated with the change in the water vapor concentration as the depth of the BL changes.  This present work uses LES to examine how well that residual assumption compares to the actual sum of those two entrainment terms derived from spatial averages of the LES output. We highlight the importance of the second entrainment term in closing the mixed layer budget, especially during the morning transition, and show that the residual assumption does not represent entrainment flux only but rather a total entrainment term when the boundary layer depth is changing.
 
## Science Question(s)
Does the sum of entrainment terms close the mixing diagram?
What is the relationship between the two terms?

## Hypothesis (or Hypotheses)
Ent2 will be crucial to closure

## Methods
LES - MicroHH, no LSM, forced by VARANAL
Mixing diagrams from the below mixed layer budget equation

$$\frac{\partial \overline{\phi}}{\partial t} = \left.\frac{\partial \overline{\phi}_{ml}}{\partial t}\right|_{LS} + \left.\frac{\overline{w'\phi'}}{z_i}\right|_{Sfc} - \left.\frac{\overline{w'\phi'}}{z_i}\right|_{top} + (\frac{\partial z_i}{\partial t}-\overline{w_i}) \frac{(\overline{\phi}_{top} - \langle\overline{\phi}\rangle)}{z_i}$$

## Summary
