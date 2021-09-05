<img src="https://github.com/alinesoares1/ISTD-OC-Dataset/blob/main/imgs/workflow.png?raw=true">


# ISTD-OC Dataset
The ISTD-OC dataset is one of our contributions on "How Far Deep Learning Systems for TextDetection and Recognition in Natural Scenes are Affected by Occlusion?" published at CBDAR 2021. The dataset is derivated from a systematic methodology in which, for each image, word instances were occluded differently. The work is only a small step towards recognizing occluded texts in natural scenes robustly. Still, the proposal is sufficient for the initial analysis of current models' generalization ability in the face of occlusion.

Data partitioning (train and test) was performed following the methodology of ICDAR 2015 dataset. So, to provide occluded images through the ISTD-OC dataset, we've collected 1500 images for detection and 4468 images for recognition from the ICDAR 2015 dataset. 
**Notes**:

1. For more information and demo run step by step, check out these **[tutorials]:(https://github.com/alinesoares1/ISTD-OC-Dataset/blob/main/istdoc-text-detection.ipynb)** and **(https://github.com/alinesoares1/ISTD-OC-Dataset/blob/main/istdoc-text-recognition.ipynb)** on Google Colab/Drive.


## Datasets supported

a. [ICDAR 2015](https://rrc.cvc.uab.es/?ch=4&com=downloads)

## Requirements

- Python 3.x
- OpenCV 4.x
- Numpy

## Sample

You can directly access ISTD-OC dataset for testing **[here](https://drive.google.com/drive/folders/1GefnxQaNdP43XN2d7kT1fMDnWs1zSxHY?usp=sharing)**.

<img src="https://github.com/alinesoares1/ISTD-OC-Dataset/blob/main/imgs/sample.png?raw=true">

## Citation

If this project helped in any way in your research work, feel free to cite the following paper.

### How Far Deep Learning Systems for Text Detection and Recognition in Natural Scenes are Affected by Occlusion? ([here]https://doi.org/10.1007/978-3-030-86198-8_15)

This work address the issue of occlusions in scene text identification.We first investigated and evaluated the effectiveness of four popular deep archi-tectures for scene text detection, i.e., PAN, CRAFT, PSENet, EAST, and others four for scene text recognition task, i.e., ROSETTA, RARE, CRNN, and STAR-Net on ICDAR 2015 dataset without any generated occlusion. Second, we present as a contribution of this work a methodologyto  implement  occlusion  and  generate  large  datasets  of  occluded  scene  text  innatural images from benchmarks such as ICDAR 2015. This brand new dataset,named Incidental Scene Text Dataset - Occlusion (ISTD-OC), contains 15000 images for detection and 65450 cropped word images for recognition, with levelsof occlusions in an interval that ranges from zero to a hundred percent. We alsostreamline the research over the ISTD-OC dataset by conducting a comparativeevaluation on the eight state-of-the-art text identification algorithms reviewed, a baseline reference for future research in the specific occlusion problem.

```
Geovanna Soares A., Leite Dantas Bezerra B., Baptista Lima E. (2021) How Far Deep Learning Systems for Text Detection and Recognition in Natural Scenes are Affected by Occlusion?. In: Barney Smith E.H., Pal U. (eds) Document Analysis and Recognition – ICDAR 2021 Workshops. ICDAR 2021. Lecture Notes in Computer Science, vol 12916. Springer, Cham. https://doi.org/10.1007/978-3-030-86198-8_15
```
