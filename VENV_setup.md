# How to Set Up a Virtual Environment
**NOTE:** Any terminal commands are for Linux/Unix-like platforms

Running these scripts in a virtual environment can help ensure the integriy of your packages, and also make sure the packages youre using for these scripts do not interfere with those you have installed system wide.

If you familiar wiht setting up virtual environments, the list of packages to install can be found towrads the end of this document.

I reccomend running a **conda** environment, and the instructions for setting one up are as follows:

### Install MiniForge3

If you already have miniforge3 or miniconda3 installed (or any other conda version) feel free to skip to the next section.

MiniForge is a community lead version of MiniConda, utilizing conda-forge as the default channel, which is useful for many of the packages we will be installing later.

To install MiniForge3, download the installer for your operating system from [this link](https://conda-forge.org/download/) and follow their installation instructions.

Once installed, run the command ```conda init``` to add the conda command to your path.

### Create the Environment

To create the conda environment for this repository, ensure you have downloaded [nisar_venv.yml](nisar_venv.yml), then run the command ```conda env create -f nisar_venv.yml```, which will create an environment named nisar_venv with all the required pacakges installed.

From there, to activate your environment run the command ```conda activate nisar_env```, and the base path at the left side of your terminal should display the name of your environment. 


### Install Dependencies

Instead of using the nisar_venv.yml, if you want to run the notebooks in a different environment or mannually install the packages, use ```conda install package-name``` in your active environment to install each package in the following list (or just run the following command directly)

To install all of the packages needed, run the following command: 

**pending**



**Seamus Gillis**  
Cornell University  
skg72@cornell.edu
