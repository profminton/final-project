# Final Project: Rotation and Tides
###### *Due: Friday, Dec. 9, 2022 by 5:00pm*

>##### Note on your GitHub repository
> I have left the structure of the project up to you, but *it should have structure*. If you are unsure where to start, use a template. A popular one is [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/), which also includes a rationale behind the structure it encourages you to create. I recommend reading it, even if you don't follow it exactly.
>
> Be sure to include a description of your code in the `README.md` file.

*Pick any two of the following three problems*

### Tidal evolution modeling of the Pluto-Charon system.
Implement a tidal evolution model and reproduce Figures 3 and/or 4 from Cheng, Lee, & Peale (2014). 

Cheng, W.H., Lee, M.H., Peale, S.J., 2014. Complete tidal evolution of Pluto-Charon. Icarus 233, 242–258. https://doi.org/10.1016/j.icarus.2014.01.046


### Milankovitch Cycles.
Add rotational kinematics to your symplectic integrator. 

Use your updated code to plot the eccentricity ($e$), the sine of the longitude of periapsis ($\sin\varpi$), and the obliquity ($\epsilon$) of Earth for 800 ky. 

Compare your plots with the top three curves here:
https://en.wikipedia.org/wiki/Milankovitch_cycles#/media/File:MilankovitchCyclesOrbitandCores.png

>  One approach would be to follow Following Sections 2.3 and 2.4 of Bolmont et al. (2015) and adding *just only the rotational* model (no tides or GR). The `Mercury` n-body code used in that paper is a symplectic integrator based on the Wisdom-Holman symplectic map.


Bolmont, E., Raymond, S.N., Leconte, J., Hersant, F., Correia, A.C.M., 2015. Mercury-T : A new code to study tidally evolving multi-planet systems. Applications to Kepler-62. A&A 583, A116. https://doi.org/10.1051/0004-6361/201525909


### Planet Migration and Resonant Capture: The origin of Pluto's Peculiar Orbit

Implement an artificial migration term to your symplectic integrator. Use it to reproduce Fig. 1 from Malhotra (1993).

Malhotra, R., 1993. The origin of Pluto’s peculiar orbit 365, 819–821. https://doi.org/10.1038/365819a0
