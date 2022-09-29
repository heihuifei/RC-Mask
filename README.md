# RC-Mask: Rotated-Count-MaskRCNN For Chromosome Segmentation

This repo is using for chromosome instance segmentation.
## Abstract
Chromosome karyotyping plays a vital role for birth
defect diagnosis and biomedical research, in which segmentation is
an indispensable task. Current state-of-the-art segmentation methods
suffer from bottlenecks due to the small size and polymorphism of
the chromosomes, and the overlapping chromosomes is a critical
obstacle as well. This work proposes an algorithm for preprocessing dataset and a segmentation network termed RC-Mask for
chromosome segmentation. The RC-Mask extends Mask R-CNN by
adding a branch for predicting count in parallel with the existing
branches, moreover, we add orientation information to both the object
detection and semantic segmentation branches. Without tricks, RCMask achieves state-of-the-art segmentation accuracy on original
chromosome dataset(63.9%mAP), which outperforms all existing on
chromosome automatic segmentation. Code is available at https://github.com/heihuifei/RC-Mask


