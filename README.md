# Calibration light scattering - cell diameter
The goal of this project is to use an optimized Mie theory to infer particle cell size from forward scatter measurements. In order to use Mie theory, an optimization method was developed to minimize the difference between forward scattering measured by SeaFlow and estimated using Mie theory. The optimization step was necessary because the optical geometry of the flow cytometer is not precisely known. An optimization procedure was conducted to scale the dimensionless values of forward scatter, in which the differences between the Mie-modeled and measurement-derived forward scatter were minimized. We used SeaFlow measurements of calibration particles of known refractive index and size. These particles includes 7 sizes of polystyrene beads (0.3, 0.5, 0.75, 1, 1.83, 3.1 and 5.7 µm in diameter; n = 1.6003). Using this optimization, a lookup table of theory-based solutions for particle forward scattering was created over a range of particle diameter detectable by the SeaFlow (0.3 - 10 µm) and index of refraction applicable to marine phytoplankton (n=1.38 +/- 0.3). To evaluate the applicability of these solutions, we compared Mie-predicted cell diameter to observations of 9 phytoplankton cultures using Coulter Counter.

The Mie-predicted cell diameter using the mid-range index of refraction (1.38) was in good agreement with observations (R<sup>2</sup> = 0.90, p < 0.0001). Discrepancies were observed for the diameter of the larger phytoplankton (<i>Geminifera cryophila</i> and <i>Thalassiosira weissflogii</i>) and the smaller cyanobacteria (<i>Prochlorocococcus</i> MIT9312 and MED4 and <i>Synechococcus</i> WH8012), which, for larger phytoplankton, may be related to inappropriate approximation of the spherical shape of particles used in the Mie theory (Quirantes and Bernard, 2004), while for small cyanobacteria, direct measurements of cell diameter were less reliable as they were near the detection limit of  the Coulter Counter Multisizer.

![alt text](Mie-scatter.png "Mie-predicted cell diameter compared to observations")

***François Ribalet, Megan Schatz and Jarred Swalwell contributed to this project.***
