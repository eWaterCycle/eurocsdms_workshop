(intro)=
# Welcome to the eWatercycle demonstration for the EuroCSDMS Workshop

_EuroCSDMS workshop "What does the next generation of environmental models look like?" organized by Centre for Ecology and Hydrology (CEH) in October 2024 at Rydall Hall, Lake District, UK_
_Interactive eWatercycle demonstration given by dr. ir. Bart Schilperoort (Netherlands eScience Center) and dr. ir. Rolf Hut (Delft University of Technology)_

This 'teachbook' (an online combination of markdown text and yupiter notebooks that form a coherent whole) contains all the material used during the interactive workshop introducing eWaterCycle during the EuroCSDMS workshop "What does the next generation of environmental models look like?". The material in this book is intended to showcase how the eWaterCycle platform is build upon the BMI interface to provide hydrologist with an easy to use way to work with their, and each others, models and data. 

The platform is explained using a standard "hello world" example, or in the case of hydrology: calculating a hydrograph. [This notebook](oneModel/example_model_run_HBV.ipynb) shows how to run the simple HBV conceptual model for any region available in the Caravan dataset. Naturally, we choose the region where the workshop is held and model the discharge of river Leven at Newby Bridge.

Branching out from this first case, additional experiments that highlight different uses of the eWaterCycle platform are presented through the [Additional Experiments](additional/additionalExperiments.md) page.

On most pages that contain python code (ie. yupiter notebooks), one can find a little 'rocket' icon. If you click on the yupiterhub icon that appears when hovering over the rocket, you will be taken to a server that runs the notebook you are looking at, allowing you to directly run it and interact with it. The server running these notebooks will only be online during the workshop and workshop participants will be provided with login details to this server. If you are reading this page and are interested in running these notebooks, you can either:

- setup your own server that runs eWaterCycle (or install it on a big enough laptop / desktop computer). See the information in the infrastructure repository on how to setup eWaterCycle
- send us an email at [questions@ewatercycle.org](mailto:questions@ewatercycle.org) where you explain your interest in eWaterCycle and we can (hopefully) help you further.
- in the near future we hope to provide access to eWaterCycle through other platforms such as the Destination Earth platform of the European Union. Stay tuned!