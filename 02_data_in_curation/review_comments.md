# Curation_Demo Dataset Submitted: MONTH DD, 20xx

Raw data uploaded to the 'Curation_demo' repo for review

## Curation Dataset(s) creation
* Began with uploaded raw data to check formatting
* Checked mapping to FEDEFL and technosphere classification
* Nomenclature and/or classification edits proposed
* Checked metadata and data quality indicators for completeness
* Cross-checked life cycle impact assessment (LCIA) results
* Checked for data loading, display, indexing in platform

# NREL Dataset Review Suggestions: MONTH DD, 20xx

* NREL has reviewed the datasets for:
  * adherence to agreed-upon conventions related to naming, categorization, nomenclature, and structure per the Federal LCA Commons guidelines within the openLCA data model
  * dataset consistency for indexing, display, and search

* NREL used the [openLCA Flow Mapping](https://www.openlca.org/flow-mapping-feature/) to map the submitted data to current USLCI version for technosphere flows and FEDEFL for elementary flows. Suggested changes were made to the [01_raw_data](https://github.com/uslci-admin/curation_demo/tree/master/01_raw_data) and are noted below as the initial review feedback related to the above-mentioned factors. Please see the [Data_in_Curation](https://github.com/uslci-admin/curation_demo/master/02_data_in_curation) file rendered in .zolca format for import to openLCA; note, this folder also includes this review comment file. 


## General Feedback

Check total processes: #[xx]
Check total products: #[xx]

Check source citation(s) URL links, where applicable: 
- [ ] **Source 1:** [insert url link]
- [ ] **Source 2:** [insert url link]
- [ ] **Source 3:** [insert url link]

### Process 1: Categorization & Intermediate Flow Nomenclature

* NAICS categorization-propose [CODE xxxx](https://www.census.gov/naics/)
* Adapt FLCAC-compliant nomenclature for process & product names; see: [USLCI Metadata Guidance General Information](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/field-conventions/general-info.md#general-information)


### Process 2: Categorization & Intermediate Flow Nomenclature

* NAICS categorization-propose [CODE xxxx](https://www.census.gov/naics/)
* Adapt FLCAC-compliant nomenclature for process & product names; see: [USLCI Metadata Guidance General Information](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/field-conventions/general-info.md#general-information)

## MetaData
Please see the USLCI Data Submission Handbook [Metadata Guidance Tables](https://github.com/uslci-admin/uslci-content/blob/dev/docs/submission_handbook/02-how-to-publish-in-the-uslci.md#metadata-guidance-tables)

## LCIA Checks
The LCIA check is performed in openLCA v1.10.3 using the [USLCI_20xx_Qx_staging] (most recent, not yet published version) for linking background processes and applying the TRACI v2.1 adapted for the [Federal Elementary Flow List (FEDEFL)](https://cfpub.epa.gov/si/si_public_record_report.cfm?dirEntryId=347251&Lab=NRMRL&subject=Land%20and%20Waste%20Management%20Research&showCriteria=0&searchAll=Waste%20Management%20or%20Nitrogen%20Management%20or%20Contaminated%20Sites%20or%20Ground%20Water%20or%20Materials%20Management%20or%20Sediment%20Toxicity&sortBy=revisionDate&startIndex=51&displayIt=Yes) nomenclature as per the USLCI Curation Process.

  * **_Curation_demo_process, at plant_** GWP check is [xx] kg CO2 eq vs [xx] kg CO2 eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** CED check is [xx] MJ vs [xx] MJ per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** AP check is [xx] kg SO2 eq vs [xx] kg SO2 eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** EP check is [xx] kg N eq vs [xx] kg N eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** FWEcoTox check is [xx] CTUeco eq vs [xx] CTUeco eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** HH cancer check is [xx] CTUcancer eq vs [xx] CTUcancer eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** HH PM check is [xx] CTUnoncancer eq vs [xx] CTUnoncancer eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** ODP check is [xx] kg CFC-11 eq vs [xx] kg CFC-11 eq per provider in [Insert Source Platform]
  * **_Curation_demo_process, at plant_** Smog check is [xx] kg O3 eq vs [xx] kg O3 eq per provider in [Insert Source Platform]


NOTE: results cross-check differs from source platform result when curated LCI is missing CUTOFF burdens e.g., for non-USLCI linked intermediate flows

**The LCIA checks and final publishable version (JSON-LD zip file) of the updated dataset(s) curated for publishing in the USLCI_20xx_Qx_vx are in the [03_data_final folder](https://github.com/uslci-admin/curation_demo/tree/master/03_data_final) of this GitHub repository**


---

## Processes
### Process: 
#### General comments
#### General information
##### General information
###### Name
###### Description
###### Category
###### Version
###### UUID
###### Last change
###### Infrastructure process
##### Quantitative reference
###### Quantitative reference
##### Time
###### Start date
###### End date
###### Description
##### Geography
###### Location
###### KML
###### Description
##### Technology
###### Description
#### Inputs/Outputs
##### General comments
##### Inputs
##### Outputs
#### Administrative information
##### Administrative information
###### Intended application
###### Data set owner
###### Data generator
###### Data documentor
###### Publication
###### Access and use restrictions
###### Project
###### Creation date
###### Copyright
#### Modeling and validation
##### Modeling and validation
###### Process type
###### LCI method
###### Modeling constants
###### Data completeness
###### Data selection
###### Data treatment
##### Data source information
###### Sampling procedure
###### Data collection period
##### Process evaluation and validation
###### Reviewer
###### Data set other evaluation
##### Sources
#### Parameters
#### Allocation
#### Social aspects

---

## Flows
### General comments
### Inputs
### Outputs
## Background data
### Sources
### Actors

