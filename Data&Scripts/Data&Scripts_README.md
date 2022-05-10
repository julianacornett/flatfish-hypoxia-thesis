# Data & Scripts

This folder includes all data files (.csv) and R scripts (.Rmd) used for data analysis and figures in the written thesis, divided into the following categories:

## [ElkhornSlough_DO](ElkhornSlough_DO)

Data was downloaded from the [National Estuarine Research Reserve Centralized Data Management Office](http://cdmo.baruch.sc.edu/dges/).

* [**"ElkhornSloughDO.Rmd"**](ElkhornSlough_DO/ElkhornSloughDO.Rmd) (Figure 1 in thesis)

_R script for plotting dissolved oxygen (DO) data from 4 water quality monitoring sites in Elkhorn Slough across different timescales._

* [**"AzevedoPond_DO_5.1.21_8.31.21.csv"**](ElkhornSlough_DO/AzevedoPond_DO_5.1.21_8.31.21.csv)

_csv file including DO data from Azevedo Pond water quality monitoring site from summer 2021, including station name, timestamp, and DO (mg/L)._

* [**"NorthMarsh_DO_5.1.21_8.31.21.csv"**](ElkhornSlough_DO/NorthMarsh_DO_5.1.21_8.31.21.csv)

_csv file including DO data from North Marsh water quality monitoring site from summer 2021, including station name, timestamp, and DO (mg/L)._

* [**"SouthMarsh_DO_5.1.21_8.31.21.csv"**](ElkhornSlough_DO/SouthMarsh_DO_5.1.21_8.31.21.csv)

_csv file including DO data from South Marsh water quality monitoring site from summer 2021, including station name, timestamp, and DO (mg/L)._

* [**"VierraMouth_DO_5.1.21_8.31.21.csv"**](ElkhornSlough_DO/VierraMouth_DO_5.1.21_8.31.21.csv)

_csv file including DO data from Vierra Mouth water quality monitoring site from summer 2021, including station name, timestamp, and DO (mg/L)._

## [Compensatory_Mechanisms](Compensatory_Mechanisms)

Data was collected by Juliana Cornett following protocols in the [Ventilation](/Protocols/Ventilation) and [Blood_Sampling](/Protocols/Blood_Sampling) folders. 

* [**"Englishsole_AllVars.csv"**](Compensatory_Mechanisms/Englishsole_AllVars.csv)
* [**"Speckledsanddab_AllVars.csv"**](Compensatory_Mechanisms/Speckledsanddab_AllVars.csv)

_csv files for both species with fish ID, Species, DO (mg/L), weight (g), total length (cm), pre- and post-exposure ventilation rate (breaths/min), hematocrit (%), L-Lactate in muscle tissue (uM), superoxide dismutase (SOD) in gill tissue (U/mL), and hypoxia-inducibel factor-1a (HIF) in brain tissue (pg/mL)._

* [**"CompensatoryPlots_LinearModelScatterplots.Rmd"**](Compensatory_Mechanisms/CompensatoryPlots_LinearModelScatterplots.Rmd) (Figures 6 & 7 in thesis)

_R script for linear models & scatterplots of DO versus compensatory mechanism (hematocrit or pre- to post-exposure change in ventilation rate), to test for relationship between DO level and compensatory mechanism measurements._

* [**"CompensatoryPlots_ANOVATukeyBoxplots.Rmd"**](Compensatory_Mechanisms/CompensatoryPlots_ANOVATukeyBoxplots.Rmd) (Figures 4 & 5 in thesis)

_R script for ANOVA with Tukey post-hoc test & boxplots of DO versus compensatory mechanism (hematocrit or pre- to post-exposure change in ventilation rate), to compare mean compensatory mechanism measurements between DO levels._

## [Metabolic_Responses](Metabolic_Responses)

Data was collected by Juliana Cornett following protocols in the [Respirometry](/Protocols/Respirometry) folder. 

* [**"Englishsole_Allometric.csv"**](Metabolic_Responses/Englishsole_Allometric.csv)

_csv file including fish ID, length (cm), weight (g), and pre-exposure MMR & SMR (mgO2/kg/hr)._

* [**"AllometricScaling.Rmd"**](Metabolic_Responses/AllometricScaling.Rmd) (Table 3 in thesis)

_R script for linear models of fish size, length (cm) and weight (g), versus pre-exposure metabolic parameters, MMR & SMR (mgO2/kg/hr), to test for significance of allometric scaling._

* [**"Englishsole_Metabolic.csv"**](Metabolic_Responses/Englishsole_Metabolic.csv)

_csv file including fish ID, DO (mg/L), and pre- and post-exposure MMR & SMR (mgO2/kg/hr)._

* [**"MetabolicPlots_LinearModelScatterplots.Rmd"**](Metabolic_Responses/MetabolicPlots_LinearModelScatterplots.Rmd) (Figure 9 in thesis)

_R script for linear models & scatterplots of DO versus pre-exposure, as well as pre- to post-exposure change, metabolic parameters (SMR, MMR, and aerobic scope in mgO2/kg/hr), to test for relationship between DO level and metabolic parameters._

* [**"MetabolicPlots_ANOVATukeyBoxplots.Rmd"**](Metabolic_Responses/MetabolicPlots_ANOVATukeyBoxplots.Rmd) (Figure 8 in thesis)

_R script for ANOVA with Tukey post-hoc test & boxplots of DO versus pre-exposure, as well as pre- to post-exposure change, metabolic parameters (SMR, MMR, and aerobic scope in mgO2/kg/hr), to compare mean metabolic parameters between DO levels._

## [Biochemical_Changes](Biochemical_Changes)

Data was collected by Juliana Cornett following protocols in the [Tissue_Assays](/Protocols/Tissue_Assays) folder. 

* [**"Englishsole_AllVars.csv"**](Biochemical_Changes/Englishsole_AllVars.csv)
* [**"Speckledsanddab_AllVars.csv"**](Biochemical_Changes/Speckledsanddab_AllVars.csv)

_csv files for both species with fish ID, Species, DO (mg/L), weight (g), total length (cm), pre- and post-exposure ventilation rate (breaths/min), hematocrit (%), L-Lactate in muscle tissue (uM), superoxide dismutase (SOD) in gill tissue (U/mL), and hypoxia-inducibel factor-1a (HIF) in brain tissue (pg/mL)._

## [PCA](PCA)

This analysis includes data from multiple physiological response measurements. 

* [**"Englishsole_AllVars.csv"**](PCA/Englishsole_AllVars.csv)
* [**"Speckledsanddab_AllVars.csv"**](PCA/Speckledsanddab_AllVars.csv)

_csv files for both species with fish ID, Species, DO (mg/L), weight (g), total length (cm), pre- and post-exposure ventilation rate (breaths/min), hematocrit (%), L-Lactate in muscle tissue (uM), superoxide dismutase (SOD) in gill tissue (U/mL), and hypoxia-inducibel factor-1a (HIF) in brain tissue (pg/mL)._



