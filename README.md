# FAce SEmantic SEGmentation repository

Welcome to the webpage of the *FAce Semantic SEGmentation* (*FASSEG*) repository.

The FASSEG repository is composed by two datasets (*frontal01* and *frontal02*) for frontal face segmentation, and one dataset (*multipose01*) with faces in multiple poses.

If you use our datasets, please cite our works ([1] or [2], depending on the dataset).

## Dataset descriptions

### Frontal01

Frontal01 contains **70 labeled frontal faces** and the original RGB images. Original faces are mainly taken from the MIT-CBCL [3] and FEI [4] datasets. 

**This is the dataset we used in our work [1]**. Images are organized in two folders - train and test - matching the division we adopted in the paper.

### Frontal02

Frontal02 is an *"high-precision 01"*. It contains the same images as in Frontal01 but with much more precise segmentations.


### Multipose01
Multipose01 contains more than **200 labeled faces in multiple poses**. Original faces are taken from the Pointing04 database [5].

**This is the dataset we used in our work [2]**. Images are organized in two folders - train and test - matching the division we adopted in the paper.

*Our advice is: if you need to compare with our results in [1], choose Frontal01. If you need a dataset to train a frontal face segmenter, choose Frontal02. If you are working with multiple head poses, choose Multipose01.*


## References

[1] *Khalil Khan*, *Massimo Mauro*, *Riccardo Leonardi*, **"Multi-class semantic segmentation of faces"**, IEEE International Conference on Image Processing (ICIP), 2015

[2] *Khalil Khan*, *Massimo Mauro*, *Riccardo Leonardi*, **"Head pose estimation through multiclass face segmentation"**, IEEE International Conference on Multimedia and Expo (ICME), 2017. 
*In collaboration with [YonderLabs](http://www.yonderlabs.com)*

[3] *MIT Center for Biological and Computational Learning (CBCL)*, **MIT-CBCL database**, [http://cbcl.mit.edu/software-datasets/FaceData2.html](http://cbcl.mit.edu/software-datasets/FaceData2.html)

[4] *Centro Universitario da FEI*, **FEI database**,
[http://www.fei.edu.br/~cet/facedatabase.html](http://www.fei.edu.br/~cet/facedatabase.html)

[5] *Nicolas Gourier, Daniela Hall, and James L Crowley*, **“Estimating face orientation from robust detection of salient facial structures”** in FG Net Workshop on Visual Observation of Deictic Gestures. FGnet (IST– 2000–26434) Cambridge, UK, 2004, pp. 1–9.
