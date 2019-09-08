## Welcome to PRIME-RE
### The PRIMatE Research Exchange

The preprocessing and analysis of nonhuman primate (NHP) magnetic resonance imaging (MRI) data presents some unique challenges.
PRIME-RE aims to provide a description of the main difficulties and the existing solutions associated with each of the processing steps commonly performed on NHP MRI data.
PRIME-RE is maintained and curated by members of the [PRIME-DE consortium](http://fcon_1000.projects.nitrc.org/indi/indiPRIME.html). 

![logo](images/social_preview_image.png)

### [Atlases](#atlases)

### [Structural preprocessing](#structpreproc)
  
  - [What is it about?](#description)
  - [Issues linked to NHP imaging](#issues)
  - [Steps](#steps)
      - [Preparation of data (Cropping, deoblique…)](#preparation)
      - [Registration to template](#registration)
      - [Brain extraction / skull stripping](#extraction)
      - [Segmentation (GM, WM, CSF? Subcortical?bone, non brain soft tissue? air?)](#segmentation)
      - [Surface generation](#surf)
      - [Morphometry measures (thickness, curvature etc)](#measures)
      
  - [Pipelines Reviews](#structlinks)  
  - [Communication](structural_preprocessing/data_preparation.md#communication)
   

### [fMRI preprocessing](#functionalpreproc)


<a name="atlases"></a>
# Atlases
Comming soon...


<a name="structpreproc"></a> 
# Structural preprocessing
<a name="description"></a> 
## What is it about?
Several steps to obtain a segmented brain with possibility to create surfaces

<a name="issues"></a> 
## Issues specific to NHP imaging
- non standard orientation: sphinx position, oblique orientation
<p align="center"><img src="images/misorientation.png" width="400"></p>
- strong intensity bias due to a huge variety of coils used
<p align="center"><img src="images/bias.png" width="250"></p>
- large FOV / non brain tissue
<p align="center"><img src="images/non_brain.png" width="250"></p>

<a name="steps"></a> 
## Steps
<a name="steps"></a> 
### Preparation of data (Cropping, deoblique…)

- **What is is about?**

- **Solutions**


<a name="registration"></a>  
### Registration to template
<a name="extraction"></a> 
### Brain extraction / skull stripping
<a name="segmentation"></a> 
### Segmentation (GM, WM, CSF? Subcortical?bone, non brain soft tissue? air?)
<a name="surf"></a> 
### Surface generation
<a name="measures"></a> 
### Morphometry measures (thickness, curvature etc)

<a name="structlinks"></a> 
## Links to pipelines
    &rarr; Direct Access:
     - [Chris' notebook html](structural_preprocessing/surfaces_and_flatmaps_notebook/Surfaces_and_Flatmaps.html) - [Download Chris' notebook](structural_preprocessing/surfaces_and_flatmaps_notebook/Surfaces_and_Flatmaps.ipynb)
     - [macapype](https://github.com/BastienCagna/macapype)

<a name="functionalpreproc">
# Functional Preprocessing









