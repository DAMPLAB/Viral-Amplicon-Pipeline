# Viral-Amplicon-Pipeline

## Introduction
This repository details the viral amplicon sequencing pipeline developed by the DAMP Lab for the Connor Lab, both at Boston University. The experimental goal is to extract RNA from viral samples, generate cDNA and amplicons, and prepare the amplicons for sequencing. This is a fully automated process that includes eight automated scripts that were created and validated in the DAMP Lab utlizing Hamilton Microlab STAR liquid handlers. The full Standard Operating Procedures can be found in the [Full Pipeline SOPs and Intermediary Steps Document](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Full%20Pipeline%20SOPs%20and%20Intermediary%20Steps.pdf). 

## Pipeline Steps with Approximate Times
Automated Scripts are linked. 
1. Sample Receipt & Aliquot ~20 minutes
3. [RNA Extraction](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/COVID-19%20Extraction%20V1.2.0_DAMP.pkg)~2 hours and 15 minutes
4. [RT and cDNA Generation](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/cDNA_Generation_V1.0.0.pkg)  ~1 hour and 20 minutes
5. [Target Amplicon Generation](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Amplicon_Generation_V1.0.0.pkg) ~5 hours and 10 minutes
6. QC Checkpoint: Gel Electrophoresis ~2 hours and 20 minutes
7. [Ampure XP Bead Clean-Up](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Amplicon_cleanup_V1.1.1.pkg)~2 hours
8. [Sample Dilution](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Dilution%20Method%20V1.0.pkg) ~25 minutes
9. [Library Preparation](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/NEB_Next_UltraExpress_V1.1.2.pkg)~4 hours and 15 minutes
10. [Quantification](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Quantification%20Prep_V3.0.pkg) ~1 hour and 10 minutes
11. [Sample Dilution](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Dilution%20Method%20V1.0.pkg) (Optional) ~25 minutes
12. [Pooling](https://github.com/DAMPLAB/Viral-Amplicon-Pipeline/blob/main/Automated%20Methods/Normalization%20%26%20Pooling_V1.0.pkg) ~30 minutes
13. QC Checkpoint: TapeStation/Fragment Analysis ~1 hour
14. Sequencing Preparation ~30 minutes
15. Sequencing ~17 hours

## Software and Equipment Requirements
1. [VENUS 4](https://www.hamiltoncompany.com/automated-liquid-handling/venus?utm_source=adwords&utm_medium=ppc&utm_campaign=Lab+Products+%7C+PMax+%7C+Neuros+Syringes&utm_term=&hsa_tgt=&hsa_grp=&hsa_mt=&hsa_cam=21775976635&hsa_ver=3&hsa_src=x&hsa_net=adwords&hsa_kw=&hsa_acc=3619911770&hsa_ad=&gad_source=1&gclid=Cj0KCQiA0--6BhCBARIsADYqyL8x_XI-vGPap9jN3weV95XyDSR36x4UDW4TnXtLXsfFdZPAu9UiRd8aAp_VEALw_wcB) (or above)
2. [Hamilton Liquid Handler](https://www.hamiltoncompany.com/automated-liquid-handling?utm_source=adwords&utm_medium=ppc&utm_campaign=Hamilton+Brand&utm_term=hamilton%20microlab%20star&hsa_tgt=kwd-300748043222&hsa_grp=142615525106&hsa_mt=e&hsa_cam=18784057107&hsa_ver=3&hsa_src=g&hsa_net=adwords&hsa_kw=hamilton%20microlab%20star&hsa_acc=3619911770&hsa_ad=632048298447&gad_source=1&gclid=Cj0KCQiA0--6BhCBARIsADYqyL9t6VdduvIgd-eYfusQEbt35I36IWIO4vagP-zNa0F9UXrty8XAEakaAuR9EALw_wcB) and Appropriate Modules ([HHS](https://www.hamiltoncompany.com/automated-liquid-handling/small-devices/hamilton-heater-shaker?srsltid=AfmBOoobjtQMeKejRbQ9oDtjxoNSHGXQGwjCxt96I6_7fh3nzo2Dl_YG), [CPAC](https://www.inheco.com/cpac.html), [Magnetic Stands](https://www.alpaqua.com/magnet-plate-selector/?fwp_format=96#plate-finder))
3. Thermocycler
4. Plate Reader
5. [Agilent TapeStation](https://www.agilent.com/en/product/automated-electrophoresis/tapestation-systems/tapestation-instruments/4200-tapestation-system-228263?gad_source=1&gclid=Cj0KCQiA0--6BhCBARIsADYqyL_POQnSBvLExCDLU8Tfpy5vRMjYx6Wbc2Iy9_9JvIol4D6SUyYcbdwaAgaCEALw_wcB&gclsrc=aw.ds) or Fragment Analyzer

## Authors
* [Kristen Sheldon](https://github.com/kristenshels)
* [Courtney Tretheway](https://github.com/catretheway)
