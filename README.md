**hbf_sampledata**

This package contains sample model data for Helsinki BEM Framework (HBF).
The data are extracted from various online sources and processed as described below.
The file formats are, to some extent, explained in HBF example scripts.

The purpose of this repository and these datasets is to provide relevant geometrical models to be used for learning, how to use HBF.
The datasets were wrapped together for this repository by the author,
but the data have been collected and / or provided by others. When using these data in a publication,
acknowledge the original data as indicated below or in the original licenses of the data.
I also kindly ask you to mention this package.

I do not own these data or have any copyright to them;
please use the data according to the original licenses and conditions, summarized below.

These data are here shared for the good of scientific community. There is no guarantee of any kind.

v200929 Matti Stenroos (matti.stenroos@aalto.fi)

*hbf_samplehead_3shell_wh.mat*

The head geometry of this model is extracted from Subject 1 of the data set described in
Wakeman, D.G. & Henson, R.N. (2015). A multi-subject, multi-modal human neuroimaging dataset. Sci. Data 2:150001 doi:10.1038/sdata.2015.1.
The data is available at 
https://openneuro.org/datasets/ds000117/
under CC0 license. For this package, the data were extracted from the original package in
ftp://ftp.mrc-cbu.cam.ac.uk/personal/rik.henson/wakemandg_hensonrn/


The meshes were constructed with SPM, using scripts provided with the data. If you use the head geometry in a publication, cite the Wakeman–Henson publication and include the above
information.

Sensor geometries of a 306-channel Neuromag MEG system (as described in MNE-C software, http://mne.tools/) and 256-channel ABC EEG-layout (as described by Biosemi, http://www.biosemi.com/download/Cap_coords_all.xls, were added and coregistered manually by the author. The sensors and their coregistrations do not correspond to the sensors used in the of the Wakeman–Henson dataset.