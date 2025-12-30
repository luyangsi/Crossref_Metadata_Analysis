# Crossref Retraction Metadata Analysis

The primary motivation of this project is to advocate for the quality of indexed retraction metadata and promote awareness among the scientific community.

### Description
This Jupyter notebook is used for the clean and process the annotated sample metadata,including add extra columns to display statistic informations. Its output includes cleaned dataset, data visualization, and metadata statistic informations.

**Setup**
1. Install the proper version of Jupyter notebook (our version: 7.34.0).
2. Install the standard python libraries: os, re, collections.
3. Install third-party packages: pandas, numpy, matplotlib, and seaborn.


**Run the Code**
1. Download the "retraction-indexing-agreement" folder or clone the web URL: https://github.com/infoqualitylab/retraction-indexing-agreement.git
2. Set your working directory to  “retraction-indexing-agreement” and create data, result, src subfolders. Create subfolders for data as shown below.
3. Run the code in the src subfolder.

```
retraction-indexing-agreement/
|
├── config.json
├── data/
│   ├── coverednotindexed/
│   ├── crossref/
│   ├── engineeringvillage/ 
├── result
├── src/
│   ├── Step1_DataCollectionFromSources_and_UnionList.ipynb
│   ├── Step2_HandlingItemsWithoutDOI_ButWithPubMedID.ipynb 
```

3. Enter your email, API Keys and insttoken into the config.json file
4. Run the files in the src files
5. Install the libraries as mentioned above
6. Run the cells accordingly 

## [Tag v1.1.0](https://github.com/luyangsi/Crossref_Metadata_Analysis.git)
**Cite code v1.1.0 as:** <br>
- TODO

 **Code authors:**
 - Luyang Si (0009-0008-7883-4757) with contributions from Malik Salami (0000-0002-2329-5660).<br>

**Manuscript**
- Si, Luyang; Salami, Malik Oyewale; Schneider, Jodi. Tracking the Data Quality Landscape of 	Retracted Papers: Flag Usage in Titles and Changes in DOI Retraction Status.

