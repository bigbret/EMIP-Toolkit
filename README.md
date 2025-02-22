[![Test Passing](https://github.com/nalmadi/EMIP-Toolkit/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/nalmadi/EMIP-Toolkit/actions/workflows/test.yml)
[![Code Size](https://img.shields.io/github/languages/code-size/nalmadi/EMIP-Toolkit?color=gold)](https://github.com/nalmadi/EMIP-Toolkit)
[![Watchers](https://img.shields.io/github/watchers/nalmadi/EMIP-Toolkit?color=magenta)](https://github.com/nalmadi/EMIP-Toolkit)
[![Forks](https://img.shields.io/github/forks/nalmadi/EMIP-Toolkit?color=magenta)](https://github.com/nalmadi/EMIP-Toolkit)
[![Stars](https://img.shields.io/github/stars/nalmadi/EMIP-Toolkit?color=magenta)](https://github.com/nalmadi/EMIP-Toolkit)



# EMIP-Toolkit

**EMIP Toolkit: A Python Library for Customized Post-processing of the Eye Movements in Programming Dataset**

The use of eye tracking in the study of program comprehension in software engineering allows researchers to gain a better understanding of the strategies and processes applied by programmers. Despite the large number of eye tracking studies in software engineering, very few datasets are publicly available. The existence of the large Eye Movements in Programming Dataset (EMIP) opens the door for new studies and makes reproducibility of existing research easier. The toolkit is specifically designed to make using the EMIP dataset easier and more accessible. It implements features for fixation detection and correction, trial visualization, source code lexical data enrichment, and mapping fixation data over areas of interest. 

[Read More...](https://www.researchgate.net/publication/350485560_EMIP_Toolkit_A_Python_Library_for_Customized_Post-processing_of_the_Eye_Movements_in_Programming_Dataset).

[![Watch the video](https://imgur.com/IcowLr3.png)](https://www.youtube.com/watch?v=wFdGyM6qUlE)

# Please Cite: 
Naser Al Madi, Drew T. Guarnera, Bonita Sharif, and Jonathan I. Maletic.2021. EMIP Toolkit: A Python Library for Customized Post-processing of the Eye Movements in Programming Dataset. In ETRA ’21: 2021 Symposium on Eye Tracking Research and Applications (ETRA ’21 Short Papers), May25–27, 2021, Virtual Event, Germany. ACM, New York, NY, USA, 6 pages. https://doi.org/10.1145/3448018.3457425


# Features:
The toolkit is specifically designed to make using the EMIP dataset easier and more accessible by providing the following functions:
 
 
 - Parsing raw data files from the EMIP dataset into Experiment, Trial, and Fixation containers.
    
 - Customizable dispersion-based fixation detection algorithm implementation according to the manual of the SMI eye tracker used in the data collection.
   
 - Raw data and filtered data visualizations for each trial.
    
 - Performing hit testing between fixations and AOIs to determine the fixations over each AOI.
        
 - Customizable offset-based fixation correction implementation for each trial.
    
 - Customizable Areas Of Interest (AOIs) mapping implementation at the line level or token level in source code for each trial.
    
 - Visualizing AOIs before and after fixations overlay on the code stimulus.
    
 - Mapping source code tokens to generated AOIs and eye movement data.
    
 - Adding source code lexical category tags to eye movement data using [srcML](https://www.srcml.org/). srcML is a static analysis tool and data format that provides very accurate syntactic categories (method signatures, parameters, function names, method calls, declarations and so on) for source code. We use it to enhance the eye movements dataset to enable better querying capabilities. 

 - Downloading specific datasets from the [EMIP-Toolkit replication package](https://osf.io/j6vt3/) and other data sources.


# Examples and tutorial:
The Jupyter Notebook file "EMIP Toolkit Examples.ipynb" contains examples and a tutorial on using the EMIP Toolkit. The file describes the required file structure and raw EMIP files and metadata from http://emipws.org/.

# Suggested Workflow
Below is the suggested workflow for contributing to this project: 

1. Fork the repository to your account.
2. Make changes to the main branch in your forked repo.
3. Test that everything still works.
4. Create a pull request to merge the updated code/changes to the main EMIP repository.
5. Respond to questions with project maintainers to get pull-requests accepted.



# Corrected Dataset:
The directory “Corrected EMIP Dataset” includes our second contribution of a filtered, corrected, and processed version of the EMIP dataset.

# Support
Before opening a new issue, make sure to check to see if someone has opened a similar or the same issue. This will stop issues from being repeated. If there is no corresponding issue, open a new thread and members from the community will comment. 

# Road Map
Road Map for the Future of the Project To Be Determined.


# Requirements and Installation: 
**The Following Packages are Required:**


**[numpy](https://numpy.org/)**

**[pandas](https://pandas.pydata.org/)**

**[matplotlib](https://matplotlib.org/downloads.html)**

**[Pillow](https://pypi.org/project/Pillow/)**

**[requests](https://pypi.org/project/requests/)**

**[tqdm](https://pypi.org/project/tqdm/)**

# Documentation and Usage
For in-depth instructions on installation and building the documentation, see the **[EMIP Toolkit Documentation Style Guide](https://github.com/bigbret/EMIP-Toolkit/wiki/EMIP-Toolkit-Documentation-Style-Guide)**.

# Contributing 
We welcome contributions from anyone, even if you are new to open source. Please read our **[Contributing](https://github.com/bigbret/EMIP-Toolkit/wiki/Contributing)** page and the **[EMIP Toolkit Documentation Style Guide](https://github.com/bigbret/EMIP-Toolkit/wiki/EMIP-Toolkit-Documentation-Style-Guide)** before getting started. If you are new and looking for some way to contribute, a good place to start is to look at some of the current issues. 

# Adding Dataset
Please take a look at our **[Adding a Dataset](https://github.com/bigbret/EMIP-Toolkit/wiki/Adding-a-Dataset)** page for instructions on how to add new datasets to the repository. 

# License
To be decided. 


