# ClusterModel: package dedicated to provide a model of the thermal and non-thermal gas in the clusters. 


- model.py : 
	main code that defines the class Cluster
    
- model_admin.py : 
        subclass that defines administrative tools
   
- model_modpar.py : 
        subclass that handles model parameters functions 
        
- model_phys.py : 
    subclass that handles the physical properties of the cluster
    
- model_obs.py : 
    subclass that handles the observational properties of the cluster
    
- model_plots.py : 
        plotting tools for automatic outputs

- model_title.py : 
	title for the module

- ClusterTools :
    Repository that gather several useful libraries

- notebook :
	Repository where to find Jupyter notebook used for validation/exemple. 

## Install
To install these tools, just fork the repository to your favorite location in your machine.
The software depends on standard python package (non-exhaustive list yet):
- astropy
- numpy
- scipy
- pickle
- pprint
- os
- re
- matplotlib

But also:
- ebltable (see https://github.com/me-manu/ebltable)
- healpy

In the case of Xray outputs, it will be necessary to have the XSPEC software installed.
