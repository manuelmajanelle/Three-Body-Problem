Reproducing the figure-8 solution to the three-body problem using Julia

Carl Justin Palpal-latoc and Ma. Janelle Manuel*

Objective: To reproduce the figure-8 solution to the three-body problem
What can you learn from the project:
(1) How to formulate a physical system (particularly the three-body problem) as a computational
problem (particularly by numerically solving the corresponding differential equations)
(2) How Julia can be more advantageous than Python when it comes to simulating physical systems

Key Results:
(1) Implement an ODE solver using the RK4 method.
(2) Plot the solution to the three-body problem (when the particles are of equal masses) obtained
using RK4 method, particularly replicate the figure-8 plot [1].
(3) Quantify the efficiency of Python against Julia in reproducing the figure-8 plot.

Importance in physics:
N-body interactions are ubiquitous in nature. The case of N=3 has no closed general solution [2]
(elevating the importance of numerical methods) but it is not difficult to imagine a situation
dominated particularly by N=3 interacting bodies (e.g. moon-earth-spacecraft or moon-earth-sun).

References:
[1] Chenciner, Alain; Montgomery, Richard (2000). &quot;A remarkable periodic solution of the three-body
problem in the case of equal masses&quot;. Annals of Mathematics. Second Series. 152 (3): 881–902.
doi:10.2307/2661357.
[2] Barrow-Green, June (2008), &quot;The Three-Body Problem&quot;, in Gowers, Timothy; Barrow-Green, June;
Leader, Imre (eds.), The Princeton Companion to Mathematics, Princeton University Press, pp. 726–728.
