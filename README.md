
# CHEUI-public
## If you want to access the code, please send us an e-mail requesting access:

CHEUI is software package for characterization of m6A and m5C RNA modifications using nanopore direct-RNA sequencing.
CHEUI has two software functionalities:
* CHEUI-solo can be used to detect m6A and m5C modifications at single read resolution in one condition.
* CHEUI-diff can be used to detect differential m6A/m5C between two conditions. 

# CHEUI: Methylation (CH<sub>3</sub>) Estimation Using Ionic current <img src="https://github.com/comprna/CHEUI/blob/master/misc/CHEUI_logo.png" width="280" height="250">


**About CHEUI**

CHEUI (Methylation (CH<sub>3</sub>) Estimation Using Ionic current) is an RNA modification detection software. CHEUI can be used to detect m6A/m5C in single conditions, or detect differential m6A/m5C between any two conditions. CHEUI uses a two-stage deep learning method to detect m6A and m5C transcriptome-wide at single-read and single-site resolution, without any sequence constrains.

------------------------------------------
# Dependencies
------------------------------------------
```
python=<3.5
numpy==1.19.2
pandas==1.2.2
tensorflow==2.4.1
keras==2.4.3
```

------------------------------------------
# Outline of CHEUI-solo and CHEUI-diff
------------------------------------------
 <img src="https://github.com/comprna/CHEUI/blob/master/misc/pipeline_CHEUI-solo+diff_github.png" width="900" height="500">


