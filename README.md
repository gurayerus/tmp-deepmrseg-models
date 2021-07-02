# DeepMRSeg Model Repository

This repository is a collection of models pre-trained using the [DeepMRSeg package](https://github.com/CBICA/DeepMRSeg), a generic Deep Learning Package designed for MR image segmentation. Each model is pre-trained for a different segmentation task. Training was done using large multi-site image datasets and carefully created/collected/verified ground-truth segmentations for these images. 

### Usage

Users can run a model for a specific task on their MR images using the tools provided as part of the [DeepMRSeg package](https://github.com/CBICA/DeepMRSeg). This process involves installing the DeepMRSeg package, calling the download script with the selected task as input, and calling the application script with the downloaded model and user images as input. Please see [DeepMRSeg README file](https://github.com/CBICA/DeepMRSeg#readme) for the details.

### Segmentation Tasks/Models <a name="seg_tasks"/>

This table lists segmentation tasks/models that are included in this model repository. Please note that this table is expected to evolve with time, as new models for new or existing tasks will be added. To ensure reproducibility, older models for a task are also kept in the repository. These models are tagged using a model name that includes a version number and a time stamp. Using the download script, the user can download a model either by indicating the task name (to download the latest model for a task) or the specific model name (to download any selected model).

|Task Name |Model Name |Description |Date Upload |File Name |
|-|-|-|-|-|
|<b>BrainSeg</b>|deepmrseg_brain_v1.1|07/2021|A model trained for segmenting the brain mask|deepmrseg_brainmask_v1.1.zip|

<hr>

|<b>WMLesionSeg</b>|deepmrseg_wml_v1.1|07/2021|A model trained for segmenting white matter lesions|deepmrseg_wml_v1.1.zip|

<hr>

|<b>HippoSeg</b>|deepmrseg_hippo_v1.1|07/2021|A model trained for segmenting hippocampus sub-parts|deepmrseg_hippo_v2.1.zip|
|<b>HippoSeg</b>|deepmrseg_hippo_v1.1|04/2021|A model trained for segmenting hippocampus sub-parts|deepmrseg_hippo_v1.1.zip|

<hr>

|<b>DLICV</b>|deepmrseg_dlicv_v1.1|07/2021|A model trained for segmenting intra-cranial volume|deepmrseg_dlicv_v1.1.zip|
|-|-|-|-|

## Contributions
Please contact the developers for assistance if you would like to contribute to this repository by running DeepMRSeg training on your data with ground-truth labels.

# License
TODO
