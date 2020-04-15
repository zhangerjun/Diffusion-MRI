# Diffusion-MRI (dMRI)
These Jupiter notebooks include diffusion MRI data analysis to calculate __Diffusion Tensor Imaging (DTI)__, __Diffusion Kurtosis Imaging (DKI)__, __Neurite Orientation Dispersion and Density Imaging (NODDI)__, __Single-Shell 3-tissue Constrained Spherical Deconvolution (SS3T-CSD)__, and __Multi-Shell Multi-Tissue Constrained Spherical Deconvolution (MSMT-CSD)__ modeled parametric maps.

__dMRI pre-processing__ Jupiter notebook includes diffusion MRI data __denoising__ using DIPY Local PCA via empirical thresholds, susceptibility-induced distortion correction using FSL __TOPUP__ and eddy current-induced distortion and motion correction using FSL __EDDY__.

Note that, estimation of DKI, NODDI, and MSMT-CSD modeled parametric maps require diffusion MRI data acquired for at least two different b-values.

### Dependencies
Python dependencies to use these jupyter notebooks are:
* dipy (https://dipy.org/)
* nipype (https://nipype.readthedocs.io/en/latest/)
* FSL (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL)
* AMICO (https://github.com/daducci/AMICO)
* MRtrix3 (https://www.mrtrix.org/)
