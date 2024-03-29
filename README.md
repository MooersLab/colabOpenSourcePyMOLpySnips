# colabOpenSourcePyMOLpySnips

## Library of PyMOL Python snippets for installing and running Open Source PyMOL on Google Colab via a Colab notebook

### version 0.3
### Click [here](https://github.com/MooersLab/colabpymolpysnips/edit/main/README.md) for the notebook for the Incentive PyMOL.

Click on Colab bage to open notebook on Colab:
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mooerslab/colabOpenSourcePyMOLpySnips/blob/main/colabOpenSourcePyMOLpySnips02.ipynb)

### Change 2023 May 14
Note that on 2023 May 14, Colab was using Python3.10. 
I changed the path in the script.

###
You will have to create a python env using python3.10 if you install open source pymol locally:

```bash
conda create -n pymol310 python=3.10 
conda -c conda install -c conda-forge pymol-open-source
```
### Back to this notebook

See the first cell in the notebook for install instructions.
I checked that this still works on 1 September 2022.


The `installPyMOL` snippet will install PyMOL with one click of a button.
The install process takes 5-10 minutes, so be patient.
A progress bar monitors the progress of the installation. 

This readme file is a work in progress.

Pre-repuisite: a Google Drive account.


### Step 1: Click on the above colab link
This action will open the snippet notebook on Colab.
The top of the screen should look like the following:

<p align="center"><img src="images/topOFSnippetNotebook.png"></p>


### Step 2: Copy the snippet notebook to Google Drive

Use the `File/Save copy in Drive` pulldown menu item. 
If you run some code cells, you might get a message like the following:

<p align="center"><img src="images/saveSnippetNotebookToGoogleDrive.png"></p>

Ignore this warning. Click on `run anyway`i
<p align="center"><img src="images/ignoreWarningAboutAuthorship.png"></p>


### Step 3: Paste the URL of the snippet notebook into the settings

Paste the URL onto the line `Custom snippet notebook URL`:

<p align="center"><img src="images/loadedNotebookSettings.png"></p>


### Step 4: Open a new Colab notebook

<p align="center"><img src="images/openNewNotebook.png"></p>


### Step 5: Seach for the installPyMOL snippet

<p align="center"><img src="images/searchInstallPyMOL.png"></p>


### Step 6: Insert the installPyMOL snippet into the new notebook and run

<p align="center"><img src="images/installPyMOLOpenSource.png"></p>


This step takes 5-10 mintues. Ignore this warning:

<p align="center"><img src="images/ignoreThisError.png"></p>


### Step 7: Insert the testPyMOL snippet and run

<p align="center"><img src="images/testPyMOL.png"></p>

The result look like the following image:

<p align="center"><img src="images/testResult.png"></p>


### Step 8: Save finished notebook to Google Drive or download the Colab notebook



## Related Repos

- [easypymol](https://github.com/MooersLab/EasyPyMOL/edit/master/README.md)
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts)
- [pymolsnips](https://github.com/MooersLab/pymolsnips)
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips)
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips)
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips)
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips)
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips)
- [PyMOLwallhangings](https://github.com/MooersLab/PyMOLwallhangings)

