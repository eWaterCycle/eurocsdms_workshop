(intro)=
# Additional Experiments

Next to the simple "run a model" tutorial we provide a number of notebooks to demonstrate more advanced uses of eWaterCycle. The purpose of all these notebooks is to demonstrate what little changes are needed to go from a 

- Generating forcing from CMIP for climate change impact studies. In this notebook we make little changes to the tutorial notebook to not use ERA5 re-analysis data as forcing input, but rather use data from the CMIP models to do climate change impact studies.
- Calibrate a model using observational data. In this notebook we run the tutorial model a thousand times with different parameter sets to find the optimal parameter set linking model output to observations.
- Running a distributed, more complex model. In [this notebook](pcrglobwb/example_model_run_pcrglobwb.ipynb) we run the PCRGlobWB distributed model developed by Utrecht University for a lot of global hydrology studies, focussed on the UK.
