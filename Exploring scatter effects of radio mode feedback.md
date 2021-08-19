# August 19th summary
Note: all plots in this exploration phase are the result of running Dark Sage SAM on mini-millennium merger trees (62.5 Mpc box). Because of the size of the box, I can run the model and get it to output results within less than five minutes.

# Black hole mass as a function of stellar mass 
![](https://i.imgur.com/5J7YZQb.png)

LHS panel: fiducial model for both Dark Sage (orange) and TNG300-1 (purple). The dotted line shows the median of the distribution, while the shaded regions show the 68th and 95th percentiles. Here we see that the scatter in black hole mass in TNG galaxies is much tighter than the one found in Dark Sage. Dark Sage has its largest scatter spanning three orders of magnitude at fixed stellar mass of 10^10 solar masses.

RHS panel: same relation but for a simulation run that excludes AGN radio mode feedback (in other words, the AGN contribution here is only from quasar mode). Here we see that the scatter decreases significantly with increasing stellar mass. 


# Black hole mass as a function of halo mass 
![](https://i.imgur.com/29hQA6z.png)

LHS panel: same description as above. We find that binning by halo mass decreases the black hole mass scatter significantly. Now, surprisingly, both TNG and Dark Sage have similar black hole mass-halo mass relations and scatters, with TNG producing massive galaxies and black holes not seeing in Dark Sage (but this could be explained by the simulation box size and/or resolution?) 

RHS panel: Like in the LHS panel, the scatter in black hole mass is larger at low halo masses and decreases with increasing halo masses. 

---

# Specific star formation rate as a function of stellar mass
![](https://i.imgur.com/0VBemqO.png)

LHS panel: we find a large scatter in sSFR at fixed stellar mass below 10^11 in both models with the median differing by 0.5 dex. Note that I hardcoded all galaxies with zero SFR to have logsSFR = -12 in both models. Between 10-10.5, we see that TNG galaxies become quenched. 

RHS panel: we find that the scatter is consistently large in Dark Sage compared to the fiducial model. The scatter does decrease above stellar masses of 10^11. 

# Specific star formation rate as a function of halo mass
![](https://i.imgur.com/VbM9sQo.png)

LHS: we see that the scatter in TNG galaxies is reduced significantly with increasing stellar mass, similar to Dark Sage galaxies.


RHS: the scatter in sSFR is reduced significantly with increasing stellar mass

---
# Cold gas mass as a function of stellar mass
![](https://i.imgur.com/SwdctQL.png)

LHS: 


RHS: 


# Cold gas mass as a function of halo mass
![](https://i.imgur.com/AK0BDzf.png)

LHS:

RHS: