# FASSEG dataset

Welcome to the webpage of the FAce Semantic SEGmentation (FASSEG) dataset.

The FASSEG dataset is made available here in 3 versions:

- **V1** contains 70 labeled faces and the original RGB images. Original faces are mainly taken from the MIT-CBCL [3] and FEI [4] datasets. **This is the dataset we used in our paper** [1]. Images are organized in two folders - train and test - matching the division we adopted in the paper.

- **V2** is an *"high-precision V1"*. It contains the same images as the V1 but it's much more precise in the segmentations.

- **V3** contains labeled faces in multiple poses. Original faces are taken from the Pointing04 database [5]. **This is the dataset we used in our paper** [2]. Images are organized in two folders - train and test - matching the division we adopted in the paper.

Our advice is: if you need to compare with our results in [1], choose V1. If you need a dataset to build your frontal face segmentation models, choose V2. If you need multiple poses, choose V3. 

In any case, if you use our datasets, please cite our work ([1] or [2], depending on the dataset).


[1] *Khalil Khan*, *Massimo Mauro*, *Riccardo Leonardi*, **"Multi-class semantic segmentation of faces"**, International Conference on Image Processing (ICIP), 2015

[2] *Khalil Khan*, *Massimo Mauro*, *Riccardo Leonardi*, **"Head pose estimation through multiclass face segmentation"**, IEEE International Conference on Multimedia and Expo (ICME), 2017

[3] *MIT Center for Biological and Computational Learning (CBCL)*, **MIT-CBCL database**, [http://cbcl.mit.edu/software-datasets/FaceData2.html](http://cbcl.mit.edu/software-datasets/FaceData2.html)

[4] *Centro Universitario da FEI*, **FEI database**,
[http://www.fei.edu.br/~cet/facedatabase.html](http://www.fei.edu.br/~cet/facedatabase.html)

[5] *Nicolas Gourier, Daniela Hall, and James L Crowley*, **“Estimating face orientation from robust detection of salient facial structures”** in FG Net Workshop on Visual Observation of Deictic Gestures. FGnet (IST– 2000–26434) Cambridge, UK, 2004, pp. 1–9.
