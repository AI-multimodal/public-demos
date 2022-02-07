# AI Multimodal Public Demos

This repository is part of [AIMM project](https://github.com/AI-multimodal): a joint and collaborative effort between scientist from [Brookhaven National Laboratory (BNL)](https://www.bnl.gov/) and [Lawrence Berkeley National Laboratory (LBL)](https://www.lbl.gov/)
Current contributors working in this project are: Dylan McReynolds and Jospeh Kleinhenz from LBL, and Dan Allan and Juan Marulanda from BNL.
Our goal is to create database for XAS data that can be used by scientist from beamlines at different Synchrtron Light Sources around the world. They will be able to use this database as a platform to share and use data to improve their research. 

We develop and used [tiled](https://blueskyproject.io/tiled/) for these demos. First, we can define Tiled as a data access service for data science tools and we use it to put together all the different data sets that we receive from beamline scientists and it helps users to avoid worrying about formatting, file structure and parsing.

Currently, we have integrated data sets provided by beamline scientist from Argonne National Laboratory (ANL), Brookhaven National Laboratory (BNL) and Lawrence Berkeley National Laboratory (LBL). Some of these scientists are: Dr. Maria Chen (ANL), Dr. Wanli Yang (LBL), Dr. Chengjun Sun (ANL), Dr. Eli Stavitski (BNL), Dr. Steve Heald (ANL). We also received a letter of support from Dr. Matt Newville from University of Chicago

The demos in this repostiory have access to both public and private data sets. You can run these sets by following the intructions below. Keep in mind that you will need authorization to access the private data sets. We will give authorization to a selective group of scientists via ORCID authetification.

You can run the examples in your browser on Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AI-multimodal/public-demos/HEAD?labpath=data-access.ipynb)

Or you can run the locally:

```
git clone https://github.com/AI-multimodal/public-demos
cd public-demos
pip install -r requirements.txt
pip install jupyterlab
jupyter lab
```
