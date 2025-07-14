NEMO modelling at ECCC-CCCMa
===========================

ECCC’s Canadian Centre for Climate modelling and analysis (CCCma;  `Centre climate modelling analysis - Canada.ca`_) uses NEMO for a number of different applications. CanNEMO is our version of NEMO that we use as the ocean and sea ice component for our global earth system model (CanESM) which is used for the Climate Model Intercomparison Project (CMIP). CanNEMO is also the ocean component for CCCma’s operational decadal predictions and for ½ of the ensemble members included in the Canadian Seasonal and Interannual Prediction System (CanSIPS), which provides seasonal predictions for Canada (the other ½ come from successive versions of the ECCC Meteorological Research Division's GEM-NEMO). Presently, we are working to develop the Canadian Three Oceans Downscaling System (CanTODS), a regional ocean domain that will cover Canada’s three oceans, that will be used for climate downscaling as well as for downscaling of seasonal to decadal predictions. 

In addition to our NEMO based physical ocean model, we develop two biogeochemistry models, the Canadian Ocean Ecosystem model (CanOE), and the Canadian Model of Ocean Carbon (CMOC). 

.. _Centre climate modelling analysis - Canada.ca: https://www.canada.ca/en/environment-climate-change/services/climate-change/science-research-data/modeling-projections-analysis/centre-modelling-analysis.html

..
  NEMO modeling activities at ECCC can be roughtly divided into short-term prediction and climate-scale. CONCEPTS is a partnership between ECCC, DFO, and DND and runs a short-term (10 days) forecast system that covers all of Canada's oceans at 1/12 degree and limited regions at 1/36. Climate-scale studies are centred at the CCCMa and use the global Earth System Model CanESM (Swart et al., 2019). More recently regional modelling activities have been introduced that utilise the CONCEPTS RIOPS grid. Biogeochemical models include CMOC (Zahariev et al, 2008) and CanOE (Christian et al, 2022).
..
  Global Climate Modelling
..
  CCCMa has been building global Earth System Models with prognostic ocean and land carbon cycles for almost two decades (Christian et al., 2010; Arora et al, 2011). The most recent published data are from CanESM5 and CanESM5-CanOE (Swart et al., 2019; Christian et al, 2022) CanESM6 is actively under development.


Model Domains
-----------------



Model Code
----------------
Our model code can be found here: `CCCma / CanESM · GitLab`_

.. _CCCma / CanESM · GitLab: https://gitlab.com/cccma/canesm


Members
-----------------
* Jim Christian (biogeochemical modelling): `Jim Christian | Directory of scientists and professionals`_ 
* Jonathan Izett (regional modelling): `Dr. Jonathan Izett | Directory of scientists and professionals`_ 
* Nicolas Lambert (global ocean): `Nicolas Lambert | Directory of scientists and professionals`_ 
* Bill Merryfield (seasonal to decadal predictions): `Dr. William Merryfield | Directory of scientists and professionals`_  
* Elise Olson (seasonal to decadal predictions): `Dr. Elise Olson | Directory of scientists and professionals`_  
* Natasha Ridenour (regional modelling): `Dr. Natasha Ridenour | Directory of scientists and professionals`_  
* Damien Ringeisen (sea ice): `Dr. Damien Ringeisen | Directory of scientists and professionals`_  
* Krysten Rutherford (biogeochemical modelling): `Dr. Krysten Rutherford | Directory of scientists and professionals`_  
* Geoff Stanley (global ocean): `Geoff Stanley | Directory of scientists and professionals`_  
* Nadja Steiner (biogeochemical modelling): `Nadja Steiner | Directory of scientists and professionals`_  
* Jean Sterlin (global ocean): `Jean Sterlin | Directory of scientists and professionals`_  
* Neil Swart (global earth system modelling): `Dr. Neil C. Swart | Directory of scientists and professionals`_  
* Duo Yang (global ocean): `Dr. Duo Yang | Directory of scientists and professionals`_ 

.. _Jim Christian | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/jim-christian
.. _Dr. Jonathan Izett | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-jonathan-izett
.. _Nicolas Lambert | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/nicolas-lambert
.. _Dr. William Merryfield | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-william-merryfield
.. _Dr. Elise Olson | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-elise-olson
.. _Dr. Natasha Ridenour | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-natasha-ridenour
.. _Dr. Damien Ringeisen | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-damien-ringeisen
.. _Dr. Krysten Rutherford | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-krysten-rutherford
.. _Geoff Stanley | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/geoff-stanley
.. _Nadja Steiner | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/nadja-steiner
.. _Jean Sterlin | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/jean-sterlin
.. _Dr. Neil C. Swart | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-neil-c-swart
.. _Dr. Duo Yang | Directory of scientists and professionals: https://profils-profiles.science.gc.ca/en/profile/dr-duo-yang



Papers
-----------------

Model documenting papers
^^^^^^^^^^^^^^^^^^


Research papers
^^^^^^^^^^^^^^^^




Arora, V., J. Scinocca, G. Boer, J. Christian, K. Denman, G. Flato, V. Kharin, W. Lee, and W. Merryfield (2011), Carbon emission limits required to satisfy future representative concentration pathways of greenhouse gases, Geophysical Research Letters, 38, doi:10.1029/2010GL046270.

Christian, J., et al. (2010), The global carbon cycle in the Canadian Earth system model (CanESM1): Preindustrial control simulation, Journal of Geophysical Research-Biogeosciences, 115, doi:10.1029/2008JG000920.

Christian, J. R., K. L. Denman, H. Hayashida, A. M. Holdsworth, W. G. Lee, O. G. J. Riche, A. E. Shao, N. Steiner, and N. C. Swart (2022), Ocean biogeochemistry in the Canadian Earth System Model version 5.0.3: CanESM5 and CanESM5-CanOE, Geoscientific Model Development, 15(11), doi:10.5194/gmd-15-4393-2022.

Swart, N., et al. (2019), The Canadian Earth System Model version 5 (CanESM5.0.3), Geoscientific Model Development, 12(11), 4823-4873, doi:10.5194/gmd-12-4823-2019.

Zahariev, K., J. Christian, and K. Denman (2008), Preindustrial, historical, and fertilization simulations using a global ocean carbon model with new parameterizations of iron limitation, calcification, and N-2 fixation, Progress in Oceanography, 77(1), 56-82, doi:10.1016/j.pocean.2008.01.007.


