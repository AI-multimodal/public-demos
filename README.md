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
  - Data access with widgets: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jmaruland/public-demos/add-new-data-access-notebook?labpath=aimm-server-data-access.ipynb)

- Or you can run the locally:

```
git clone https://github.com/AI-multimodal/public-demos
cd public-demos
pip install -r requirements.txt
pip install jupyterlab
jupyter lab
```
