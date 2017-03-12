# ESA recovery planning overview

_Data to Get an Overview of the Status of ESA Recovery Plans_

- [Metadata](#Metadata_11)
- [Description](#Description_25)
- [Variables](#Variables_38)
- [Applications](#Applications_47)
- [Archives](#Archives_53)
- [Comments](#Comments_60)

## Metadata
- **Version:** 1.0
- **Date:** 2016-09-01 
- **SHA-256:** 
    - FWS_recovery_plan_data.rds: d3910f498ba90feba9d305c8bb345514f8c7f97f6671370def52fe7648367a2e
    - NMFS_recovery_data_manual.rds: b8522b9e8d7d453d2f84c7b11250931f7631ed8ff1722f5892e8cd6c1bbf76a1
- **License:** CC-BY
- **Source:** 
    - FWS_recovery_plan_data.rds: Acquired by scraping 
    [U.S. Fish and Wildlife Service's ECOS website](http://ecos.fws.gov).
    - NMFS_recovery_data_manual.rds: Acquired by manually visiting 
    [National Marine Fisheries Service's recovery website](http://www.nmfs.noaa.gov/pr/recovery/plans.htm) 
    and entering the requisite data into a spreadsheet.

## Description

The U.S. Endangered Species Act (ESA) requires the U.S. Fish and Wildlife Service 
(FWS) and National Marine Fisheries Service (NMFS) develop recovery plan for 
ESA-listed species. Occasional reviews suggest that recovery planning and 
plan updating lags significantly. The two datasets in this project are the basis
for quantifying the degree of lag, which can inform ways to improve recovery
planning. 

The first dataset, `FWS_rerecovery_plan_data.rds`, was scraped from FWS's website
in September, 2016. The second dataset, `NMFS_recovery_data_manual.rds` was 
acquired by visiting NMFS's website and manually entering data.

## Variables

- **Date:** Date of the recovery plan
- **Title:** Recovery plan title
- **Plan_Action_Status:** A [dead] link to the recovery action database, ROAR
- **Plan_Status:** The stage of the plan, e.g., draft, final, revision
- **Doc_Link:** URL of the recovery plan
- **Species:** The scientific name of the species, as given by FWS

## Applications

Web applications using these dataset include:

- [Whitepaper/app](https://cci-dev.org/working_papers/recovery_plan_analysis.html)

## Archives

External public repositories containing these data sets:

- figshare: NA
- Zenodo: NA

## Comments

NA

[Top](#ESA_recovery_planning_overview_0)
