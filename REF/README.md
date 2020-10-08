 
                      
# ORCA2_ICE-REF
___

[Purpose](#purpose)  |  [Contact](#contact)  |  [License](#license)  |  [Configuration](#configuration) | [Input Files](#input-files)  |  [Diagnostics](#diagnostics)  | [Installation](#installation)

____

## Purpose

Testing simsar


## Contact

Markus Scheinert - mscheinert@geomar.de


## Terms of Use

**By downloading this repository and using this code you agree to the following conditions.**

The code in this project is based on the [NEMO](http://www.nemo-ocean.eu) software (Copyright (c) Centre National de la Recherche Scientifique CNRS).

The original code as well as the contribution to this code in this project are licensed under the conditions of [CeCILL](http://www.cecill.info). 

The person stated under '*Contact*' above is the owner of the intellectual property rights of these contributions and **must be informed afore** publishing and **must be cited** in every published work that is based completely or partially on the modifications and additional code provided by this configuration.

Usage is at one's own risk. 


## Configuration

|  **Characteristic** | **Specs** |
|-------------- | -------------- | 
| **Working repository** | git@github.com:mscheinert/ORCA2_ICE.git | 
| **Nemo-ocean repository** |  | 
| **Branch** | release-4.0 | 
| **Nemo-ocean revision** |  | 
| **Components** | OCE, TOP, ICE, NST | 
| **Reference Configuration** |  -  | 
| **CPP keys** |   key_si3      | 
| **Grid** | ORCA, zps (z-coordinate with partial steps) | 
| **Resolution** | 2 | 
| **Horizontal Gridpoints** | 182 x 149 | 
| **Vertical Levels** | 31 | 
| **Atmospheric Condition** | Bulk formulae formulation, NCAR algorithm   (Large and Yeager 2008) + separate runoff + Freshwater Budget Correction (Mode 2) | 
| **Time Step [s]** | 5400 | 
| **Passive Tracers** | Unknown | 
| **Number of Nests** | 0 | 



## Experiment/Simulation

<!--//DELDEL
The default settings for this experiment can be found in the [REF](REF) folder.
The modified code is located in the [MY_SRC](MY_SRC) directory.
DELDEL//-->
       
### Input Files

*  **NEMO Input File:** File names as they are expected by NEMO  
*  **Reference:** Citation for an article or report, webpage or even better: DOI  
*  **Download:** Link for direct downloading the file (no user-interaction preferred to make it script-compliant)  


| **NEMO Input File** | **Reference (DOI)** | **Download** |
| ------------------ | ------------------ | ------------------ | 
| ORCA_R2_zps_domcfg.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| data_1m_salinity_nomask.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| geothermal_heating.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| eddy_viscosity_3D.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| mixing_power_pyc.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| mixing_power_bot.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| mixing_power_cri.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| runoff_core_monthly.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| resto.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| data_1m_potential_temperature_nomask.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| weights_core_orca2_bicubic_noc.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| weights_core_orca2_bilinear_noc.nc |  ([doi:10.5281/zenodo.3767939](https://doi.org/10.5281/zenodo.3767939)) | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| v_10.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| t_10.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| q_10.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| ncar_rad.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| ncar_precip.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| slp.15JUNE2009_fill.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| sss_data.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| chlorophyll.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| decay_scale_cri.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |
| decay_scale_bot.nc |   | [download](https://zenodo.org/record/3767939/files/ORCA2_ICE_v4.2.tar?download=1) |



## Diagnostics

See [DIAG](DIAG) for some standard diagnostics from a simulation with this configuraton.

## Installation

There are plenty of ways how to install a local copy of this configuration:

1. You can [clone it with git](#install-with-git) (regardless of whether your NEMOGCM path is already under git control or not). 
2. Or you just download an archive from the web interface.  

In some cases there are different versions of the same configuration in separate branches (e.g. to reflect different NEMO revisions); **check the branches/tags** menu on the web interface or use the git branch and checkout commands to select 
the version you're interested in.


## Install with git


#### (A) NEMOGCM not under git control

If your NEMO installation **is not under git control already**, you can clone this configuration using the URL specified on the project's front page:

Go into the **configurations directory** in your local NEMO installation (`CONFIG/` for NEMO version 3, `cfgs/` for version 4) and clone this project (see the "Clone" link or button on the git webinterface to get the URL).

**EXAMPLE:** In this example, NEMO (version 4) has been installed on a separate scratch-disk (`$WORK`) and the simulation repository was hosted on github under the namespace `$GITNAMESPACE`:

~~~bash
cd $WORK/NEMO-release-4.0/cfgs
git clone git@github:${GITNAMESPACE}}/ORCA2_ICE-REF.git
cat ORCA2_ICE-REF/REF/exp_cfg.txt >> ./work_cfgs.txt
~~~

You can also specify a certain branch when cloning (e.g. `release-4.0` if it exists):

~~~bash
git clone -b release-4.0 git@github:${GITNAMESPACE}}/ORCA2_ICE-REF.git
~~~

This wil create a new configuration folder, which can be used as a reference case for **`makenemo -r`**. 
Make sure, you add this configuration  to the local registry file `cfg.txt` (NEMO version 3) or `work_cfgs.txt` (NEMO version 4) before invoking **`makenemo`**.



#### (B) NEMOGCM already under git control

If your **NEMOGCM installation is already under git control** you cannot clone a different repository into the existing working copy. 
Instead, you can use **`git subtree`** to inject files from another remote repository into a particular sub-folder of your existing working tree.

Within NEMOGCM directory:

**Option - With git commands**

~~~bash
cd $WORK/NEMO-release-4.0
git remote add -f remote_ORCA2_ICE-REF git@git.geomar.de:NEMO/EXP/ORCA2_ICE-REF.git   # add remote
git subtree add --prefix CONFIG/ORCA2_ICE-REF remote_ORCA2_ICE-REF release-4.0:-master --squash     # donwload master branch into sub-folder
cat cfgs/ORCA2_ICE-REF/REF/exp_cfg.txt >> cfgs/work_cfgs.txt
~~~

> In this case, you keep the information from where you have downloaded the reference configuration (see \`git remote -v\`).

Or even shorter, without keeping remote source information (not recommended):

~~~bash
cd $WORK/NEMO-release-4.0
git subtree add --prefix cfgs/ORCA2_ICE-REF git@git.geomar.de:NEMO/EXP/ORCA2_ICE-REF.git release-4.0:-master --squash
cat cfgs/ORCA2_ICE-REF/REF/exp_cfg.txt >> cfgs/work_cfgs.txt
~~~


#### Other revisions

The revision that will be installed, is the most recent one from the **master** branch. 
If you're seeking another branch/revision of this configuration (e.g. an older one), you can browse available branches/tags via the web-interface or list alternative 
branches on the command line and swap available branches/tags easily with \`checkout\`:

~~~bash
cd ORCA2_ICE-REF
git branches -r
git checkout otherBranch
~~~

Note: *origin/HEAD* in the output listing is not a branch in its own but points to the default branch (master branch in most cases).
        
        