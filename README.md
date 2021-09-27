[![DOI](https://zenodo.org/badge/323421269.svg)](https://zenodo.org/badge/latestdoi/323421269)


This repository contains data and data analysis for the manuscript:

## Variation in susceptibility among three Caribbean coral species and their algal symbionts indicates the threatened *Acropora cervicornis* is particularly susceptible to elevated nutrients and heat stress
#### Authors: Ana M. Palacio-Castro, Caroline E. Dennison, Stephanie M. Rosales, Andrew C. Baker

#### Journal: _Coral Reefs_ [40(5),1601-1613](https://doi.org/10.1007/s00338-021-02159-x)  
#### Pre-print: _bioRxiv_ [doi:10.1101/2021.05.10.443445](https://doi.org/10.1101/2021.05.10.443445)
-----
<br>

### Description:

In this study, we examined the effects of pre-exposure to elevated nutrients (NH~4~ and NH~4~ + PO~4~ for >2 months at 26 °C), followed by heat stress (31.5 °C for 3-weeks) on three Caribbean corals: *A. cervicornis*, *O. faveolata*, and *S. siderea*. 

We aimed to compare the effects of these combined stressors on coral survivorship, and associated algal symbiont communities (community composition, abundance, and function). 

</br>

### Repository content:

#### 0.LabNotebooks:

Contains daily note entries during the experiment

* **Acer_Nut- Notebook.pdf:** Pdf document with *A. cervicornis* notes (collection, maintenance, molecular work... )
* **Nut_Ofav-Ssid_NoteBook.pdf:** Pdf document with *O. faveolata* and *S. siderea* notes (collection, maintenance, molecular work... )


#### [1.Temperature](https://ghcdn.rawgit.org/anampc/NutrientsHeat_Caribbean/main/1.Temperature/Temperature.html):
* Contains raw temperature data (Day_Tem.csv) and code (Temperature.Rmd) for **Figure 1**

#### [2.Mortality](https://ghcdn.rawgit.org/anampc/NutrientsHeat_Caribbean/main/2.Mortality/Mortality_Script.html):

Contains raw mortality data and code for **Figure 2**

* **Mortatily_Script.Rmd:** code for survivorship analysis and **Figure 2**
* Data/**Acer_Mortality.csv:** Raw mortality data for *A. cervicornis*
* Data/**Ofav_Mortality.csv:** Raw mortality data for *O. faveolata*
* Data/**Ssid_Mortality.csv:** Raw mortality data for *S. siderea*

#### [3.YII](https://ghcdn.rawgit.org/anampc/NutrientsHeat_Caribbean/main/3.YII/YII_Script.html):
* Contains raw photochemical efficiency (*F~v~/F~m~*) data and code for **Figure 3**

* **YII_Script.Rmd:** code for *F~v~/F~m~* analysis and **Figure 3**

* YII_Data/**All_YII_data.csv:** YII values for all coral species


#### [4.Chla_Sym2](https://ghcdn.rawgit.org/anampc/NutrientsHeat_Caribbean/main/4.Chla_Sym2/Blasting.html):

Contains raw values of Chlorophyll-*a* and Symbiodiniaceae cell counts, as well as  code for **Figure 4 and 5**

* **Blasting.Rmd:** code for Chlorophyll-*a* and Symbiodiniaceae areal density analysis (**Figures 4 and 5**)
* Data/**data.csv:** Data and metadata with Chlorophyll-*a* values (ug Chlorophyll-*a*  cm^-2^ [Chl_a]) and  Symbiodiniaceae areal density values (Symbiodiniaceae cells  cm^-2^ [Sym.cm2])


#### 5.SH:

Contains raw qPCR values and code to produce the Symbiont to Host cell ratio (S/H). Inside each species folder (**Acer**, **Ofav** and **Ssid**) you can find:

* **1.spp_SH_calculation.Rmd:** code to calculate the symbiont to host cell ratio using files in **qPCR-Raw/**, and metadata in **Sample_Plates.csv**

* **2.Spp_Nut_SH_analysis.Rmd:** data analysis of the symbiont to host cell ratio, Durusdinium proportion and figures **S1 (*O.faveolata*)** and **S1 (*S. siderea*)**

* **qPCR-Raw/:** Contains the outputs from each plate run in qPCR

</br>

