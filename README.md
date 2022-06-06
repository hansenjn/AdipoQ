# ![AdipoQ](https://github.com/hansenjn/AdipoQ/blob/main/Webfiles/AdipoQ%20Logo.png?raw=true)

A simple toolbox of two ImageJ plugins for quantifying adipocyte morphology and function in tissues and in vitro.

**Note:** If you are not seeing this readme file at https://github.com/hansenjn/AdipoQ/ please visit this page to get the most recent version of and information about AdipoQ.

## Tools
- AdipoQ_Preparator_-…-SNAPSHOT.jar (Download latest release [here](https://github.com/hansenjn/AdipoQ_Preparator/releases)): An ImageJ plugin to segment objects (i.e., adipocytes, lipid droplets, nuclei) from background.
- AdipoQ_Analyzer_-…-SNAPSHOT.jar (Download latest release [here](https://github.com/hansenjn/AdipoQ_Analyzer/releases)): An ImageJ plugin to quantify objects (i.e., adipocytes, lipid droplets, nuclei) from a segmented image or a multi-channel image featuring at least one segmented chanenl.
- R markdown templates for post-hoc analysis are available [here](https://github.com/hansenjn/AdipoQ/tree/main/R%20Scripts).

All the tools are optimized for studying adipocytes in stained tissue or *in vitro* after immunofluorescent labeling. 

## How to use?

A comprehensive User Guide is available [here](https://github.com/hansenjn/AdipoQ/blob/main/User%20Guide/AdipoQ_User_Guide_V20211130.pdf).

_(Note: The User Guide is currently not up-to-date with the latest versions of AdipoQ Preparator and Analyzer. We will provide an updated version here very soon! Meanwhile, to see what changed since 30th of November 2021, when this User Guide was written, check out the release notes of the plugins when downloading the plugins. Alternatively, have a look at our up-to-date quick start guides below.)_

In addition, we provide a quick-start and an example guide for analyzing cells and histological samples.

### Analysis of cultured cells - guides
-  [Quick-start guide](https://github.com/hansenjn/AdipoQ/blob/main/User%20Guide/AdipoQ%20User%20Guide-QuickStart_fluorescent%20cells_v3.pdf) that teaches you the most important information for a first try of AdipoQ on an image of cultured cells.
-  [Example guide](https://github.com/hansenjn/AdipoQ/blob/main/User%20Guide/AdipoQ%20Walk%20Through%20Guide_fluorescent_v3.pdf) that walks you through the analysis of an example fluorescence microscopy image of cultured adipocytes using AdipoQ. The images used in the guide can be downloaded here:
    - [Day4-FI_Sh_s37.tif](https://github.com/hansenjn/AdipoQ/raw/main/User%20Guide/Example%20Files%20Cultured%20Cells/Day4-FI_Sh_s37.tif)
    - [Day0-ctrl_Sh_s174.tif](https://github.com/hansenjn/AdipoQ/raw/main/User%20Guide/Example%20Files%20Cultured%20Cells/Day0-ctrl_Sh_s174.tif)
-  Soon we will provide here also a quick-start guide for using machine-learning (StarDist)-based predictions to detect nuclei in AdipoQ. Meanwhile, please read the [Release notes for AdipoQ Preparator version v0.2.0](https://github.com/hansenjn/AdipoQ_Preparator/releases/tag/v0.2.0) as a guideline on how to use StarDist in AdipoQ.

### Analysis of histological images - guides
- [Quick-start guide](https://github.com/hansenjn/AdipoQ/blob/main/User%20Guide/AdipoQ%20User%20Guide-QuickStart_histology_v2.pdf) that teaches you the most important information for a first try of AdipoQ on an image of HE-labeled adipose tissue.
- [Example guide](https://github.com/hansenjn/AdipoQ/blob/main/User%20Guide/AdipoQ%20Walk%20Through%20Guide_HE_v2.pdf) that walks you through the analysis of an example image of HE-labeled adipose tissue with AdipoQ. The image used in the guide can be downloaded here:
    - [WT CD Test.tif](https://github.com/hansenjn/AdipoQ/raw/main/User%20Guide/Example%20Files%20Histology/WT%20CD%20Test.tif)

## How to cite?

When using any of the AdipoQ plugins or R scripts, please cite the following preprint:

Katharina Sieckmann, Nora Winnerling, Mylene Huebecker, Philipp Leyendecker, Dalila Ribeiro, Thorsten Gnad, Alexander Pfeifer, Dagmar Wachten, Jan N. Hansen. AdipoQ – a simple, open-source software to quantify adipocyte morphology and function in tissues and in vitro. _bioRxiv_ 2022.06.04.494793. doi: https://doi.org/10.1101/2022.06.04.494793.


## Source code and issues

The source code for the plugins is available in the repositories for the individual plugins:
- [AdipoQ_Preparator GitHub repository](https://github.com/hansenjn/AdipoQ_Preparator)
- [AdipoQ_Analyzer GitHub repository](https://github.com/hansenjn/AdipoQ_Analyzer)

If you encounter problems, error messages, or would like to suggest / contribute new functions please use the issue systems on the respective repositories or send an email to jan.hansen (at) uni-bonn.de.

## Copyright

Copyright (C) 2019-2022: Jan N. Hansen.

AdipoQ has been developed in the research group Biophysical Imaging, Institute of Innate Immunity, Bonn, Germany ([Lab Webpage](https://www.iiibonn.de/dagmar-wachten-lab/dagmar-wachten-lab-science)).

Contacts:

- jan.hansen (at) uni-bonn.de
- dwachten (at) uni-bonn.de

## Licenses

The plugins are published under the GNU General Public License v3.0. A copy of the license is contained in this repository.
