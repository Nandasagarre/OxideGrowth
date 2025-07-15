Modeling Oxide growth on Si using the Deal–Grove equations, This notebook explores oxide thickness evolves with time under different process parameters.
Process Parameters:
Temperature T; 
Native oxide thickness di; 
Dry or Wet oxidation; 
Diffusivity D; 
Solubility C*; 
Reaction rate constant Ks; 
Mass transfer consatnt h;

This repo explores Sio2 Oxide growth, with Deal-Grove (DG) model; 

Note: DG model is valid only at temperatures (800–1000 degree c).
For very thin oxides (<25 nm), the DG model underestimates the growth rates/ thickness;

Deal-Grove model can not satisfy the so-called thin film oxidation. It should be taken into account that in the middle of the 60's, when Deal and Grove developed their model, oxide thicknesses under 30 nm were not fabricated in the semiconductor technology. 

Hence, there was no need to predict or simulate the growth for such thin oxide films. But with shrinking device geometry also the oxide thickness is decreasing. Hence, sometime in the 80's, MOS gates with thin thicknesses were grown and so the problem became important. 

In order to handle also thin film oxditation, in this time Massoud and other people, reengineered the Deal-Grove concept. 

The yielded model is most suitable for thin oxide films, but it should be mentioned that it also works well for other oxide thicknesses. The price for this common validity is the higher complexity of this model. source: https://iue.tuwien.ac.at/phd/hollauer/node17.html


To access the Oxidation growth jupyter notebook  https://mybinder.org/v2/gh/nandasagarre/oxidegrowth/HEAD?urlpath=tree/OxideGrowth.ipynb
Temperature can be varied via Slider to visualize the oxide thickness and oxide growth rate;

Used Python; 
