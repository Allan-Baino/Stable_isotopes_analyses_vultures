
**This repository provides an analysis workflow for a published study on diet estimation for Gyps vultures in East Africa https://doi.org/10.1002/ece3.8726.**

**Brief overview**: Vultures are obligate scavenging birds that provide essential ecosystem services such as nutrient recycling and disease regulation however, 
they are among the most threatened taxa of birds (CR, IUCN Red List, 2024). Threats to their survival include poisoning and correlated effects of habitat loss and
food availability. Understanding their diet can among other things play an important role in identifying feeding locations frequented by vultures which can be useful
in delineating poisoning susceptibility/hotspots for the species. Knowledge of stable isotopes for diet ecology, frequentist and Bayesisan statistics principles are 
recommended and NOT covered in analysis workflow. Knowledge of R, and R packages such as SIDER https://doi.org/10.1111/ecog.03371, MixSIAR (manual uploaded) is 
highly recommended.

**Data description**: Biological samples from Gyps vultures (blood & feathers), muscle tissue from opportunistically sampled ungulates and other meta data data were 
collected in 2018 for approximately 10 months in two locations: Serengeti National Park and Julius Nyerere National Park formerly (Selous game reserve). Muscle tissue, 
blood and feather samples were prepared for a CNS run at SUERC on an Elementar Analyser using internal & external standards. Stable isotope data were organized into .csv
files that were imported into R for analyses.

**R script & .csv files**: R script - vulture_diet_analysis.R comprises the annotated 'how' to arrive at conclusions within the published article and data files: bf_iso_data.csv, Biomass_SER.csv, Biomass_SGR.csv, V.sources.csv, AR.blood.csv, sources.csv, AR.blood.discr.csv, AR.feathers.csv, AR.feathers.discr.csv provide the raw data.    

**END**
