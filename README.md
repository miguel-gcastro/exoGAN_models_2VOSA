# exoGAN_models_2VOSA
Extraction of EXOGAN atmospheric models for its inclusion into VOSA Planets catalogue

We have included into the VOSA (Spanish Virtual Observatory Application) Planet collection of models a portion of the 10 millions of syntetic atmospheric characterization models used by the methodology related in the paper "ExoGAN: "Retrieving Exoplanetary Atmospheres Using Deep Convolutional Generative Adversarial Networks"(2018 Zingales and Waldman). In such a way these models will rest available for the research community.

Learn more about ExoGAN at:
https://github.com/ucl-exoplanets/ExoGAN_public

ExoGAN models are composed by an spectrum and a collection of values for 7 parameters:  
"To  train  ExoGAN  on  a  wide  range  of  possible  exo-planetary atmospheres, we generated a very comprehensive  training  set  of  atmospheric  forward  models  using the TauREx retrieval code (Waldmann et al. 2015a,b).We sampled each of the seven previously mentioned forward model parameters (H2O, CO2, CH4and CO abundances, the mass of the planet Mp, the radius Rp and thetemperature Tp) 10 times within the parameter ranges denoted in table 1. This configuration yields 10^7 forward models."

In order to include a more manageable subset of models to include in the Spanish Observatory web based tool (VOSA PLANETS), we have extracted 76800 models from the 10^7 original set, according to the following criteria.

We have reduced the number of sample values for each parameter in this way:

For the Planet Temperature (Tp) all the 10 existing values were selected.
For the Planet Radius (Rp) 6 from the 10 existing values were selected, including both the floor and the top values.
For the Planet Mass (Mp) 5 from the 10 existing values were selected, including both the floor and the top values.
For the H2O, CO2, CH4 and CO abundances (Tp) 5 from the 10 existing values were selected, including both the floor and the top values.

The resulting subset of exoplanets atmospheric models (76800 models) have been added to the VOSA catalogue making it public to scientific community.
http://svo2.cab.inta-csic.es/theory/vosa/
