[![Abcdspec-compliant](https://img.shields.io/badge/ABCD_Spec-v1.1-green.svg)](https://github.com/brain-life/abcd-spec)
[![Run on Brainlife.io](https://img.shields.io/badge/Brainlife-bl.app.454-blue.svg)](https://doi.org/10.25663/brainlife.app.454)

<<<<<<< HEAD
# DIPY Workflow Wrapper

This is a Brainlife wrapper App for the [`dipy_denoise_lpca`](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_denoise_lpca/) workflow. This single wrapper is exposed through an App registered on [brainlife.io](https://brainlife.io).

- More information about DIPY : [dipy.org](https://dipy.org/)
- More information about the command line: [`dipy_denoise_lpca`](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_denoise_lpca/)

### Authors
- [Javier Guaje](https://github.com/guaje)
- [Serge Koudoro](https://github.com/skoudoro)

### Funding Acknowledgement
DIPY is publicly funded and for the sustainability of the project it is helpful to Acknowledge the use of the software. We kindly ask that you acknowledge the funding below in your publications and code reusing this code.

[![NIH-NIBIB-R01EB027585](https://img.shields.io/badge/NIH_NIBIB-R01EB027585-green.svg)](https://grantome.com/grant/NIH/R01-EB027585-01)
[![NIH-NIMH-RF1MH121868](https://img.shields.io/badge/NIH_NIMH-RF1MH121868-green.svg)](https://grantome.com/grant/NIH/RF1-MH121868-01)
[![NIH-NIMH-R01MH108467](https://img.shields.io/badge/NIH_NIMH-R01MH108467-green.svg)](https://grantome.com/grant/NIH/R01-MH108467-01)
[![NSF-BCS-1734853](https://img.shields.io/badge/NSF_BCS-1734853-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1734853)
[![NSF-EEC-1720625](https://img.shields.io/badge/NSF_BCS-1720625-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1720625)
[![NSF-OAC-1916518](https://img.shields.io/badge/NSF_OAC-1916518-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1916518)
[![NSF-IIS-1912270](https://img.shields.io/badge/NSF_IIS-1912270-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1912270)
[![NSF-IIS-1636893](https://img.shields.io/badge/NSF_IIS-1636893-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1636893)

### Citations
We kindly ask that you cite the following article and the articles in the following [link](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_denoise_lpca/) when publishing papers and code using this code.

1. Avesani, P., McPherson, B., Hayashi, S. et al. The open diffusion data derivatives, brain data upcycling via integrated publishing of derivatives and reproducible open cloud services. Sci Data 6, 69 (2019). [https://doi.org/10.1038/s41597-019-0073-y](https://doi.org/10.1038/s41597-019-0073-y)
=======
# Dipy Denoise Diffusion MRI using LPCA

The App uses the Local Principal Component Analysis (LPCA) method to denoise diffusion-weighted magnetic resonance imaging data.

### Authors
- [Serge Koudoro](skoudoro@iu.edu)
- [Javier Ricardo Guaje Guerra](jrguajeg@iu.edu)

### Contributors
- [Soichi Hayashi](soichih@gmail.com)

### Funding Acknowledgement
brainlife.io is publicly funded and for the sustainability of the project it is helpful to Acknowledge the use of the platform. We kindly ask that you acknowledge the funding below in your code and publications. Copy and past the following lines into your repository when using this code.

[![NSF-BCS-1734853](https://img.shields.io/badge/NSF_BCS-1734853-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1734853)
[![NSF-BCS-1636893](https://img.shields.io/badge/NSF_BCS-1636893-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1636893)
[![NSF-ACI-1916518](https://img.shields.io/badge/NSF_ACI-1916518-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1916518)
[![NSF-IIS-1912270](https://img.shields.io/badge/NSF_IIS-1912270-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1912270)
[![NIH-NIBIB-R01EB029272](https://img.shields.io/badge/NIH_NIBIB-R01EB029272-green.svg)](https://grantome.com/grant/NIH/R01-EB029272-01)

### Citations
We ask that you the following articles when publishing papers that used data, code or other resources created by the brainlife.io community.

1. Garyfallidis, E., Brett, M., Amirbekian, B., Rokem, A., van der Walt, S., Descoteaux, M., Nimmo-Smith, I., & Dipy Contributors (2014). Dipy, a library for the analysis of diffusion MRI data. Frontiers in neuroinformatics, 8, 8. [https://doi.org/10.3389/fninf.2014.00008](https://doi.org/10.3389/fninf.2014.00008)

2. Avesani, P., McPherson, B., Hayashi, S. et al. The open diffusion data derivatives, brain data upcycling via integrated publishing of derivatives and reproducible open cloud services. Sci Data 6, 69 (2019). [https://doi.org/10.1038/s41597-019-0073-y](https://doi.org/10.1038/s41597-019-0073-y)
>>>>>>> fb6748e0ac24b9acad971db83123d66e09c1b4f4

## Running the App

### On Brainlife.io

You can see a list of [DIPY Apps currently registered on Brainlife](https://brainlife.io/apps#dipy). Find the App that you'd like to run and click "Execute".

### Running Locally (on  your machine)

To run this command, you can simply type:

```bash
singularity exec -e docker://brainlife/dipy:1.1.1 dipy_denoise_lpca [your_args]
```

## Input

To see the documentation of all the arguments, follow this [link](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_denoise_lpca/).

## Output

All output files will be generated according to the passed arguments, as explained [here](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_denoise_lpca/).

### Dependencies

<<<<<<< HEAD
This App requires [singularity](https://www.sylabs.io/singularity/) to run.

#### DIPY is licensed under the terms of the BSD license. Please see the [LICENSE file](https://github.com/dipy/dipy/blob/master/LICENSE).
=======
This app runs on [singularity](https://www.sylabs.io/singularity/).

### DIPY
- This is a Brainlife wrapper App stemming from the [`dipy_denoise_lpca`](https://dipy.org/documentation/latest/reference_cmd/dipy_denoise_lpca/) workflow.
- This single wrapper is exposed through an apps registered on [Brainlife.io](https://brainlife.io).
- More information about DIPY : [https://dipy.org/](https://dipy.org/).
- More information about the command line `dipy_denoise_lpca`: [Command line Reference](https://dipy.org/documentation/latest/reference_cmd/dipy_denoise_lpca/).
>>>>>>> fb6748e0ac24b9acad971db83123d66e09c1b4f4
