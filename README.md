# AI Multimodal Public Demos

This repository is part of [AIMM project](https://github.com/AI-multimodal): a joint and collaborative effort between scientists from the following Labs:
- [Argonne National Laboratory (ANL)](https://www.anl.gov/): Advanced Photon Source (APS) and Center for Nanoscale Materials (CNM)
- [Brookhaven National Laboratory (BNL)](https://www.bnl.gov/): Center for Functional Nanomaterials (CFN) and National Synchrotron Light Source II (NSLS-II)
- [Lawrence Berkeley National Laboratory (LBL)](https://www.lbl.gov/): Advanced Light Source (ALS)

The current contributors and authors working in this project are:
- ANL:
  - Maria Chan, Steve Heald, Nicholas Schwarz, Chengjun Sun, Inhui Hwang, Yiming Chen
- BNL:
  - Eli Stavitski, Daniel Allan, Stuart Campbell, Deyu Lu, Xiaohui Qu, Shinjae Yoo, Matthew Carbone, Juan Marulanda, Zhu Liang, Fanchen Meng
- LBL:
  - Dylan McReynolds, Wanli Yang, Joseph Kleinhenz

<!-- Our goal is to create database for XAS data that can be used by scientist from beamlines at different Synchrtron Light Sources around the world. They will be able to use this database as a platform to share and use data to improve their research. -->
Our goal is to enable and accelerate scientific discovery by leveraging large, complex multimodal datasets generated across BES synchrotron facilities. We are developing shared, transferrable infrastructure to store, curate, analyze, interpret and disseminate the data.

We integrated with [Tiled](https://blueskyproject.io/tiled/) for these demos. Tiled is a data access service for data science tools and we use it to put together all the different data sets that we receive from beamline scientists and it helps users to avoid worrying about formatting, file structure and parsing.

<!-- Currently, we have integrated data sets provided by beamline scientist from Argonne National Laboratory (ANL), Brookhaven National Laboratory (BNL) and Lawrence Berkeley National Laboratory (LBL). Some of these scientists are: Dr. Maria Chen (ANL), Dr. Wanli Yang (LBL), Dr. Chengjun Sun (ANL), Dr. Eli Stavitski (BNL), Dr. Steve Heald (ANL). We also received a letter of support from Dr. Matt Newville from University of Chicago -->

This repository contains both public and private data sets. Currently, we have enabled the XAS data library of Dr. Matt Newville ([source](https://github.com/XraySpectroscopy/XASDataLibrary)) for public access in our server. 

You can run all the data sets by following the intructions below. Keep in mind that you will need authorization to access the private data sets. We will give authorization to a selective group of scientists via ORCID authetification.

- You can run the examples in your browser on Binder:

  - Data access example: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AI-multimodal/public-demos/HEAD?labpath=data-access.ipynb)
  - Data access with widgets: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AI-multimodal/public-demos/HEAD?labpath=aimm-server-data-access.ipynb)
  <!-- - Write arrays and dataframes: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AI-multimodal/public-demos/HEAD?labpath=array-dataframe-writer.ipynb)-->

- Or you can run the locally:

```
git clone https://github.com/AI-multimodal/public-demos
cd public-demos
pip install -r requirements.txt
pip install jupyterlab
jupyter lab
```


## Funding acknowledgement

This research is based upon work supported by the U.S. Department of Energy, Office of Science, Office Basic Energy Sciences, under Award Number FWP PS-030. This research used resources of the Center for Functional Nanomaterials (CFN), which is a U.S. Department of Energy Office of Science User Facility, at Brookhaven National Laboratory under Contract No. DE-SC0012704.

### Disclaimer

The Software resulted from work developed under a U.S. Government Contract No. DE-SC0012704 and are subject to the following terms: the U.S. Government is granted for itself and others acting on its behalf a paid-up, nonexclusive, irrevocable worldwide license in this computer software and data to reproduce, prepare derivative works, and perform publicly and display publicly.

THE SOFTWARE IS SUPPLIED "AS IS" WITHOUT WARRANTY OF ANY KIND. THE UNITED STATES, THE UNITED STATES DEPARTMENT OF ENERGY, AND THEIR EMPLOYEES: (1) DISCLAIM ANY WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE OR NON-INFRINGEMENT, (2) DO NOT ASSUME ANY LEGAL LIABILITY OR RESPONSIBILITY FOR THE ACCURACY, COMPLETENESS, OR USEFULNESS OF THE SOFTWARE, (3) DO NOT REPRESENT THAT USE OF THE SOFTWARE WOULD NOT INFRINGE PRIVATELY OWNED RIGHTS, (4) DO NOT WARRANT THAT THE SOFTWARE WILL FUNCTION UNINTERRUPTED, THAT IT IS ERROR-FREE OR THAT ANY ERRORS WILL BE CORRECTED.

IN NO EVENT SHALL THE UNITED STATES, THE UNITED STATES DEPARTMENT OF ENERGY, OR THEIR EMPLOYEES BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, CONSEQUENTIAL, SPECIAL OR PUNITIVE DAMAGES OF ANY KIND OR NATURE RESULTING FROM EXERCISE OF THIS LICENSE AGREEMENT OR THE USE OF THE SOFTWARE.

