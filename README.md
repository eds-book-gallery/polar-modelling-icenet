<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Sea ice forecasting using IceNet</h1>
</div>

<p align="center">
    <a href="https://github.com/Environmental-DS-Book/polar-modelling-icenet/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="https://notebooks.gesis.org/binder/v2/gh/Environmental-DS-Book/polar-modelling-icenet/main?labpath=polar-modelling-icenet.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://us-central1-b.gcp.pangeo.io/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FEnvironmental-DS-Book%2Fpolar-modelling-icenet.git&urlpath=tree%2Fpolar-modelling-icenet.git%2Fpolar-modelling-icenet.ipynb&branch=main">
        <img alt="JupyterHub" src="https://img.shields.io/static/v1.svg?logo=Jupyter&label=PangeoJupyterHub&message=2i2c&color=orange">
    </a>
    <a href="https://github.com/Environmental-DS-Book/polar-modelling-icenet/actions/workflows/render.yaml">
        <img alt="Render" src="https://github.com/Environmental-DS-Book/polar-modelling-icenet/actions/workflows/render.yaml/badge.svg">
    </a>
    <br/>
</p>

<p align="center">
    <a href="https://w3id.org/ro-id/ac327c3a-5264-40a2-8c6e-1e8d7c4b37ef">
        <img alt="RoHub" src="https://img.shields.io/badge/RoHub-FAIR_Executable_Research_Object-2ea44f?logo=Open+Access&logoColor=blue">
    </a>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/13321552/222992432-ce985964-a191-481a-b830-1438c77c8461.png?raw=True" alt="thumbnail" width="300"/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/Environmental-DS-Book/polar-modelling-icenet.git
    ```

4. Move into the cloned repository
    ```bash
    cd polar-modelling-icenet
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate polar-modelling-icenet
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.
The workflow actions were adapted from [2i2c’s hub-user-image-template](https://github.com/2i2c-org/hub-user-image-template) released under BSD-3-Clause license.