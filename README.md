# Semantic-Segmentation-of-Liver-and-Its-Tumor-Using-3D-U-Net

Abstract—In this study, I explore an experimental modification
of the U-Net model tailored for segmenting liver and its lesions in
contrast-enhanced abdominal CT scans. This adaptation employs
a unique combination of Dice Loss and Focal Loss aimed at
addressing the challenge of class imbalance between foreground
lesions and background voxels. My preprocessing approach
involves excluding training examples where the segmentation
mask is predominantly background by over 95 percent, thus
concentrating the model’s learning on clinically significant cases.
Validated on the LiTS 2017 dataset, this customized adaptation
of the U-Net model illustrates its potential in medical image
segmentation. However, it achieved moderate accuracy of 65.34%
and Intersection over Union (IoU) of 34.85%, indicating areas
for further improvement and optimization in future work.
Index Terms—liver lesion segmentation, U-Net, Dice Loss,
Focal Loss, class imbalance, high-resolution medical images, LiTS
2017 challenge.
