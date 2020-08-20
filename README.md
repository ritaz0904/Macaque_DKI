# Macaque_DKI
              
Description of the data:

The dataset was generated for the manuscript entitled "Neuroanatomical underpinning of diffusion kurtosis measurements in the cerebral cortex of healthy macaque brains" (https://www.biorxiv.org/content/10.1101/2020.07.25.221093v2.abstract) under revision in Magnetic Resonance in Medicine. This manuscipt should be cited appropriately for using the dataset.

The zipped data folder "Macaque_DKI" is split into two volumes, Macaque_DKI.7z.001 and Macaque_DKI.7z.002. Please download both volumes, click on the first downloaded volume, and unzip with 7-Zip. Both volumes will be unzipped into one folder “Macaque_DKI.”

MRI data:

&emsp;  The folder "Macaque_DKI" contains two subfolders, "Diffusion_MRI" and "MK".

&emsp;  The subfolder "Diffusion_MRI" contains raw diffusion weighted images with two b-values 1500s/mm2 and 4500s/mm2 of an ex-vivo healthy macaque brain.

&emsp;  The subfolder "MK" contains the mean kurtosis (MK) map fitted from the raw diffusion weighted images.

&emsp;  Diffusion kurtosis fitting was conducted with the fitting software "DK_fitting" provided by the same author group and publicly available at 
&emsp;  github.com/ritaz0904/DK_fitting.

&emsp;  The "Diffusion_MRI" subfolder includes 5 files:

            * b1500.hdr and b1500.img are the raw b=1500s/mm2 diffusion weighted image volumes in analyze format;
            * b4500.hdr and b4500.img are the raw b=4500s/mm2 diffusion weighted image volumes in analyze format;
            * gradient.txt is the gradient table used for each b-value.

&emsp;  The "MK" subfolder has 2 files:

            * MK.hdr and MK.img are the fitted mean kurtosis map in analyze format.

Histology data:

            * Histology data from a different healthy macaque brain is publicly available at brainmaps.org under "Macaca Mulatta" with SMI-32 stain;
            * Histology data can be downloaded for comparsion with diffusion MRI mean kurtosis map.  
              
