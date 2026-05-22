# Face Responses In Childhood

Code to reproduce the analyses presented in: "Fusiform face area development correlates with development in higher-order social brain regions".

Repository author: Lorena Jiménez Sánchez (lorena.jimenezs@ed.ac.uk).

# Directory structure

The project assumes the following file directory system:

* .Rproj.file

  * processed\_data
  * raw\_data

    * covariates
    * events
    * facescene\_contrast
    * motion
    * timecourses
  * results

    * demographics
    * figures
    * RQ1
    * RQ2
    * RQ3
  * scripts

# Scripts for data analysis

The repository consists of the following folder:

* scripts/ containing Rmarkdown/script files as following:

  * FRIC\_BaselineCharacteristics.Rmd: reports demographic and motion characteristics of final sample.
  * FRIC\_MRIvariables.Rmd: creates MRI variables i.e., functional  maturity  measures, magnitude of responses to face and scene events, inter-region  correlations  (also  referred  to  as  functional  connectivity) and lateralisation index of FFA at two statistical thresholds.
  * FRIC\_DevelopmentalChange.Rmd: characterises age-related changes in functional maturity, response magnitude to face/scene events and functional connectivity of FFA, MMPFC, STS and amygdala, as well as age-related changes in lateralisation index of FFA.
  * FRIC\_FunctionalMaturityFFA.Rmd: tests whether functional connectivity to/functional maturity of MMPFC, STS and amygdala correlates with functional maturity of FFA. Includes moderation effects of motion for main findings.
  * FRIC\_LateralisationIndexFFA.Rmd: This script tests if the FFA lateralisation index correlates with functional connectivity to or functional maturity of MMPFC, STS and amygdala.

