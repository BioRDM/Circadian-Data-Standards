# Readme in preparation
# README template - Essential (Core) Metadata Elements
> Without these 7 pieces of information, it will be hard for anyone to locate and re-use your data.

## General information section
> You can refer to the Extended metadata (below), where you add more detailed information.

### Title 
> A descriptive name given to the dataset.

### Creator
> List of dataset creators and contributors and their respective emails.   
> Use `FirstName LastName` format, each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow
- Ana Student
- Tom Thorough
- Diana Helpful *  
*corresponding author [diana.help@edu.uni.uk]

### Date  
YYYY-MM-DD
> A point in time associated with the lifecycle of the dataset.  
> Used mainly to cross-reference with other resources like Lab Notebooks or raw data.  
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g. 2023-03-25)

### Description
> Briefly describe the dataset content, including studied organism and basic methods used. 

### File Formats
> **If using standard file formats such as .csv, .fasta, .tiff, etc, you can skip this section.**  
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.    
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts still function after export.     
> **If using uncommon or proprietary formats is unavoidable, list the data file formats and explain how to open the files.**

## Dataset usage and access 

### Licence
> For data that do not include code/ software, we recommend either a CC-BY or a CC0 license: keep the text for one, delete the other!

This dataset is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, share, and adapt this dataset as long as you give appropriate credit.

>**or**

This dataset is released under the [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/). 
You are free to copy, modify, distribute, and use the data without restrictions.

> Generally, CC-BY 4.0 works well for scientific data as it states that data may be used freely, but attribution must be given to the original authors of the dataset. Another option is CC0, a licence made to reduce any legal and technical impediments to data sharing. CC0 provides creators a way to waive all their copyright and related rights in their works to the fullest extent allowed by law. Although CC0 doesn’t legally require users of the data to cite the source, it does not affect the ethical norms for attribution in scientific and research communities. i.e., it does not exempt researchers from the obligation of citing the original data authors. 

> For **code / software** we recommend [MIT licence](https://opensource.org/license/mit) for its simplicity. However, other types of open source licenses and their descriptions can be found in [Open Source Initiative ](https://opensource.org/licenses)

### Related resources 
> Include links (preferably a DOI) of any other datasets, publications and protocols that are related to this dataset.

---

# README template - Extended Metadata Elements
> Add this information to help others to understand, re-use and cite your data correctly. 

## General information section

### Purpose (Research Hypothesis)
> The overall rationale, reason, or intention for conducting a study that resulted in the data set.   
> Or the hypothesis that a study sets out to support (or disprove);

### Abstract
> A summary of the content of the dataset.  
> Should include a brief information about the biological material, technique used and measurement/experimental conditions. 
> The comprehensives details are to be recorded in sections below.
> Here we expect a short description that helps to understand the content of the dataset without its thorough examination.

### Funding Information 
This study was supported by [Funding Agency, Grant Number].

### Acknowledgments
> Add any acknowledgements

### Dataset Folder/File Overview
#### Data files list 

> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files.  
> Filenames should include extension (state the file formats used). 

#### Dataset structure

> Preferably include a directory structure similar to the one shown in the example below. When a large number of files is present, listing only main folders is fine, as long as the content of the folder is described.

 |--`/`       
 |  |--``              
 |  |--``    
         
 |--`/`  
 |  |--`SCN_control_S01`  
 |  |--`SCN_control_S02`    
 |  |--`SCN_control_S03`    
 |  |--`SCN_treatment_S01`    
 |  |--`SCN_treatment_S02`    
 |  |--`SCN_treatment_S03`    
      
## Methodological information 
### Ethical statements 
Include ethical approval number and the guidelines used to conduct the experiment. 

### Biosample description
> Description of cell lines including provenance.     


### Experimental design and conditions
> Here you will describe your experimental design. For example, if mice were divided in different groups and the treatments applied to which group. Describe the control group.   
> For any type of measurement, describe the animals that were selected for analysis and the number of samples.  
> If necessary, include separate README files for each experiment type (measured data type). For example, a separate README file for Imaging experiments and a separate README file for gene expression experiments.  
> Describe measured techniques and the measured data. Some suggestions are described next. Feel free to include new sections or delete sections that are not applicable to your work: 

#### Treatments
> Describe any specific treatment applied. For example:   
  - light pulse stimuli;  
  - phase-shifting;  
  - pharmacological interventions.
> Add timing of interventions - **use Zeitgeber time (ZT)**

   
#### Imaging
> If not described earlier in sample preparation, include a description of sample preparation and mounting for imaging or add links to corresponding protocols.
   - Imaging method: (e.g. fluorescence microscopy, bioluminescence, etc)
   - Image acquisition:   
     - Instrument used
     - Image acquisition parameters (filters used, magnification, etc.)

   - Image data:
     - Describe if you are sharing raw, processed, and/or segmented images.
     - File formats
     - Image dimensions
     - Channel information
     - Image processing methodology

#### Gene expression / Immunocytochemistry / Transcriptomics or other   
> Include all details necessary to reproduce the data. This might include links to external protocols.    
> For genomic data see [Gene expression omnibus guidelines](https://www.ncbi.nlm.nih.gov/geo/info/MIAME.html), where they describe critical elements to include in genomic datasets. 

### Data analysis
> Describe how the data was analysed including any software used and its version.  
> Include any data processing (detrending, smoothing, averaging, etc).  
> Describe the methods used for period and phase analysis.   
     
## Dataset usage and access

### Usage Instructions 
> Include guidelines for reproducing or reusing the data or to open specific file formats. 

### Citing the Dataset
> Provide citation details.

