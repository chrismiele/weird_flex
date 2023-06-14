# weird_flex

This notebook solves the version of the SSA found in Eq. 44 of MacAyeal et al. (2021), in which surface and basal elevations may be slightly out of flotational equilibrium. There is no time evolution (velocity and stress fields correspond to the input geometry only and do not approach steady state), rheology is linear, and I hard-code the vertical deflection  𝜂 instead of solving for it. The problem is solved first using pure Firedrake, and then the solution is verified with icepack. Good agreement between the two indicates that I'm modifying icepack correctly.
