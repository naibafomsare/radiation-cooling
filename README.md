# Radiation-cooling

The aim of the project is to design a system for extracting heat via radiation from a fused silica mirror that is part of an interferometric gravitational wave detector that works at room temperature.

As usual, the project has a theoretical part and an experimental one. Roughly, the general procedure for the theoretical part is the following:

1. Given the properties of fused silica, the shape of the mirror, and the power of the incoming beam, calculate the amount of heat dissipated in the mirror. The aim of the system is to be able to extract this amount of heat, or at least to reduce it to acceptable levels.
     
3. Then, it should be possible to calculate the deformation and the temperature map of the mirror. For example, see [this technical note](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiw47mF6t2CAxWWLUQIHc9PBQUQFnoECBQQAQ&url=https%3A%2F%2Fopensky.ucar.edu%2Fislandora%2Fobject%2Freports%253A7%2Fdatastream%2FPDF%2Fdownload%2Fcitation.pdf&usg=AOvVaw2-d9chybtS9aTcPbrS1V10&opi=89978449).
4. Given the temperature map, calcuate the angular distribution of the thermal radiation.
5. Then, according to the angular distribution, select a suitable place for a folding mirror and for the sink. The aim of the folding mirror is to *optimally* reflect the radiation from the mirror onto the sink.
6. Using Comsol (or the like) optimize the design of the folding mirror and sink in order maximize the *view factor* (also called *shape factor*) from the main mirror onto the sink.
7. Choose suitable coatings for the folding mirror and the sink.
8. Given the view factors, absorption coefficients and emissivities of the folding mirror and sink, use the Stephan-Boltzmann Law to calculate the temperature of the sink that would allow the extraction of the required amount of heat.
