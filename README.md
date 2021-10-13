# Data and analysis script for paper '“Digital Proxies” for validating models of past socio-ecological systems in the Mediterranean Landscape Dynamics Project'

Copyright (c). C Michael Barton, Arizona State University 2021.  

This package includes the original data and analysis scripts needed to reproduce the analyses and figures reported in the published paper (citation below).  

### Full citation of associated paper:
Barton, C. M., Ullah, I. I. T., Gauthier, N., Miller, N., Snitker, G., Esteban, I., Bernabeu Aubán, J., & Heimsath, A. M. (2021). “Digital Proxies” for validating models of past socio-ecological systems in the Mediterranean Landscape Dynamics Project. In S. Pardo Gordó & S. M. Bergin (Eds.), Simulating the Transition to Agriculture and Its Ecological and Cultural Consequences—A Collection of Recent Archaeological Research Highlighting the Application of Computational Modeling to the Spread and Establishment of Agriculture. Springer Nature.  

#### Bibtex format citation
@incollection{bartonDigitalProxiesValidating2021,
	address = {Cham, Switzerland},
	title = {'{Digital} {Proxies}' for validating models of past socio-ecological systems in the {Mediterranean} {Landscape} {Dynamics} {Project}},
	abstract = {All representations of the human past are models, whether they are in the form of narratives, equations, or computer algorithms. While we can never know the "true" past, archaeologists seek to create more reliable and useful models of the dynamics of ancient lives and societies. One of the most widely accepted ways to scientifically establish a model's validity is to compare its results or predictions against the observable, empirical, archaeological record. However, most archaeological models deal with richly dynamic, living human behavior, social relationships, and interactions with the environment, while the archaeological and associated paleoecological records are composed of fragmentary, altered, static, discarded material culture and dead plant and animal remains. This apparent incommensurability between archaeological models and the empirical data needed to validate them has long created significant challenges for establishing the credibility of archaeological explanation. In spite of ongoing advances in data collection and analysis methods, there is much we cannot change about the nature of the archaeological record. But we can modify models to generate outputs more directly comparable with this record. The Mediterranean Landscape Dynamics Project (MedLanD) has created a sophisticated computational laboratory to simulate long term dynamics of agropastoral land use and landscape evolution. To better evaluate these simulation models, we also have developed a validation instrument that creates a 'digital proxy' record based on model results. The digital proxy is analogous to extracting a digital core at specified points in the gridded, digital landscape. It simulates the accumulation over time of a proxy-like record for modeled human land-use, vegetation, landscape fire, and surface processes. Digital proxy 'cores' can be compared directly with empirical samples taken from analogous points in real world landscapes, improving our ability to validate complex models. We present an overview of our digital proxy modeling method and a test case of comparing digital and empirical data from locales in Mediterranean Spain.},
	booktitle = {Simulating the {Transition} to {Agriculture} and {Its} {Ecological} and {Cultural} {Consequences} - {A} {Collection} of {Recent} {Archaeological} {Research} {Highlighting} the {Application} of {Computational} {Modeling} to the {Spread} and {Establishment} of {Agriculture}},
	publisher = {Springer Nature},
	author = {Barton, C Michael and Ullah, Isaac I T and Gauthier, Nicolas and Miller, Nari and Snitker, Grant and Esteban, Irene and Bernabeu Aubán, Joan and Heimsath, Arjun M},
	editor = {Pardo Gordó, Salvador and Bergin, Sean M},
	year = {2021},
	note = {ZSCC: NoCitationData[s0]},
	pages = {in press},
}

## Included in this package is:

1. Data files for empirical sediment column data (sp_nv7.csv and sp_nv7.rda) and modeled proxy data (sp_nv7_allmodels_10cm.csv and sp_nv7_allmodels_10cm.rda) in csv text format and R binary format (*.rda)
2. RMarkdown script to carry out analyses and generate visualizations presented in the paper (DigitalProxies2021_analysis.Rmd).
3. An HTML file showing example output from running the Rmd with the RDA data files.

## Reproducing the analyses
Analyses were carried out using R ver. 4.1.0 and RStudio 1.4

To reproduce the analysis, make sure that the csv and Rmd files are in the same folder on your computer. Launch RStudio and set the working directory to the folder containing the csv and Red files (use RStudio functions or the R command setwd()).

You should then be able to *knit* the results to an output format of your choice.

## Contact
If you have questions you can (currently) reach the lead author of this file at michael.barton@asu.edu.
