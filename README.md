# SI-1 Methods - Full calculation
This documentation file was generated on 2020-10-13 by Kyle Proctor

-------------------
# GENERAL INFORMATION
-------------------

1. Title of Dataset 
Agrivoltaics align with Green New Deal goals while supporting investment in the US’ rural economy SI-1 Methods

2. Creator Information

Name:Kyle W. Proctor
Institution:Oregon State University
College, School or Department: Biological and Ecological Engineering
Address: 116 Gilmore Hall, 124 SW 26th St,Corvallis, OR, United States
Email:proctork@oregonstate.edu
ORCID:0000-0002-4900-6564
Role:Data curation, Formal analysis, Software, Writing

Name:Ganti S. Murthy
Institution: Indian Institute of Technology- Indore
College, School or Department: Discipline of Biosciences and Biomedical Engineering
Address: Khandwa Road, Simrol, Indore, Madhya Pradesh 453552, India
Email: Ganti.Murthy@oregonstate.edu
ORCID: 0000-0003-2774-9559
Role:Funding acquisition, Supervision, Writing- review and editing

Name:Chad W. Higgins
Institution:Oregon State University
College, School or Department: Biological and Ecological Engineering
Address: 116 Gilmore Hall, 124 SW 26th St,
Email:chad.higgins@oregonstate.edu
ORCID: NA
Role:Conceptualization, Funding acquisition, Supervision, Writing- review and editing


3. Contact Information 

Kyle Proctor (proctork@oregonstate.edu) or Chad Higgins (chad.higgins@oregonstate.edu)

-------------------
CONTEXTUAL INFORMATION
-------------------

1. Abstract for the dataset
This Jupyter Notebook is intended to accompany the publication "Agrivoltaics align with Green New Deal goals while supporting investment in the US’ rural economy".This reduced-order economic analysis estimates the total construction, operation, and energy storage costs of wide scale 
implementation of Agrivoltaic Systems in the United States. Additionally, estimates are made for potential job creation, emissions reduction, and total 
required land area of these systems. The jupyter notebook contains the full calculation used for the publication, allowing users to alter key assumptions and 
investigate the corresponding impact. 

2. Date of data collection:
This jupyter notebook does not utilize any original data. Citations for all data used can be found in the references section of the notebook. 

3. Funding sources that supported the collection of the data:
National Science Foundation (NSF) award NSF EAR 1740082
U.S. Department of Agriculture (USDA) award OREZ-FERN-852-E


--------------------------
SHARING/ACCESS INFORMATION
-------------------------- 

1. Licenses/restrictions placed on the data:
This work is licensed under a Creative Commons Attribution 4.0 International License

2. Links to publications related to the dataset:

Proctor, K.W., Murthy, G.S., Higgins, C.W.Agrivoltaics align with Green New Deal goals while supporting investment in the US’ rural economy.
Proceedings of the National Academy of Sciences of the United States Brief reports (Currently in review)

3. Links to other publicly accessible locations of the data:
Web accesible version of notebook: https://mybinder.org/v2/gh/proctork/Reduced-Order-Agrivoltaic-Cost-Estimate/master

4. Recommended citation for the data:
Proctor, K.W., Murthy, G.S., Higgins, C.W. (2020) Agrivoltaics align with Green New Deal goals while supporting investment in the US’ rural economy S1- Methods.Oregon State University.

5. Dataset Digital Object Identifier (DOI)
https://doi.org/10.7267/mc87px76j

6. Limitations to reuse
The only limitations on reuse of this content would stem from software issues, see section below on requirments to run the jupyter notebook.

--------------------------
VERSIONING AND PROVENANCE
-------------------------- 

1. Last modification date
2020-10-02

---------------------
DATA & FILE OVERVIEW
---------------------

1. File List
   A. Filename:SI-1 Methods.ipynb
   
      Short description:  see abstract      
	  
   B. Filename: SI-1 Methods.pdf
   
	  Short description:  PDF version of jupyter notebook

2. Formats       
	.ipynb (https://fileinfo.com/extension/ipynb)
	.pdf

-----------------------------------------
CODE-SPECIFIC INFORMATION: 
-----------------------------------------

1. Installation 
This notebook requires a python distribution. 
The code was developed using the anaconda distribution which can be downloaded here: https://www.anaconda.com/products/individual

The notebook was tested using the following software versions:
Anaconda 4.8.4
CPython 3.7.1
IPython 7.2.0
jupyter notebook 5.7.4

2. Requirements

The notebook requires a set of libraries but all libraries will be installed by running the code, without the user needing to do anything else.

Required libraries include:
-pandas (0.23.4)
-numpy  (1.15.4)
-ipywidgets (7.4.2)
-matplotlib (3.0.2)

3. Usage
This code looks at a situation where utility scale Agrivoltaics are used to meet 20% of US electricity generation and estimates the following:
-Total Array costs
-Costs for Lithium Ion battery storage
-Area required
-Returns from selling energy
-CO2 emission reduction
-Jobs created
