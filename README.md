# Radiation-cooling

The aim of the project is to design a system for extracting heat taking advantage of the thermal radiation that naturally and continously radiates from a fused silica mirror that is part of an interferometric gravitational wave detector that works at room temperature.

The project has a theoretical part and an experimental one. Roughly, the general procedure for the theoretical part is the following:

1. Given the properties of fused silica, the shape of the mirror, and the shape and power of the incoming beam, calculate the total amount of heat dissipated and the thermal radiant intensity (radiant flux per solid angle as a function of direction). The aim of the system is to be able to extract the exact amount of heat in an optimized way according to the 
     
3. ~~Then, it should be possible to calculate the deformation and the temperature map of the mirror. For example, see [this technical note](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiw47mF6t2CAxWWLUQIHc9PBQUQFnoECBQQAQ&url=https%3A%2F%2Fopensky.ucar.edu%2Fislandora%2Fobject%2Freports%253A7%2Fdatastream%2FPDF%2Fdownload%2Fcitation.pdf&usg=AOvVaw2-d9chybtS9aTcPbrS1V10&opi=89978449).~~

5. The folding mirrors must reflect *optimally* the radiation from the mirror into the sink, and the sink must keep it from returning to the mirror so the cooling ensues. Therefore, from the thermal radiant intensity, calculate the total solid angle the folding mirrors need to span, their shape, and the temperature and shape of the sinks, in order to extract more heat than the one deposited by the laser on the mirror. This is equivalent to saying that the *view factor* (also called *shape factor*) from the main mirror onto the sinks, via the folding mirrors, must be large enough. This is a calculation that could be done with Comsol (or the like).

With respect to the shape and material of the folding mirrors and the sinks:
- The folding mirrors can be coated with gold, wich offers an average reflectance larger than 97% from 800 nm to 20 $\rm \mu m$ [(see this link)](https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=8851).
- The sinks could be a cavities, coated in the inside with [Fractal Black](https://acktar.com/product/fractal-black/) (or the like), with an aperture big enough to allow the thermal radiation to enter. They must be connected to a conductive cooling system to regulate their temperature. 


Because radiation cooling is a well-known technique that does not require a proof-of-concept experiment, the experimental part of the project must prove it's possible to extract enough heat from a mirror *under similar circumstances than those found in a gravitational wave detector*. For example, the folding mirror and sink have to be outside of the clear aperture diameter of the main mirror, and must have certain shape and relative size with respect to it for ease of installation. Using optical components from stock, the aim would be to show that is it possible to build a cooling system with a view factor equal to the one that would be theoretically calculated for the real situation.

More discussion is needed and there's more yet to be written.
