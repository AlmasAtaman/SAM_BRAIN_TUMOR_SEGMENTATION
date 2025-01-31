# SAM_BRAIN_TUMOR_SEGMENTATION
Used Meta SAM Machine Learning Module to be able to trace an accurate segmentation of a tumor.


For this project I followed RoboFlow Tutorial on how to use Meta SAM module. The model works by making use of giving a COCO dataset of picture with brain tumors and a corresponding bounding box. The SAM module then locates the bounding box and finds the biggest mask and traces a segmentation mask on the brain tumor giving us an almost pixel perfect segmentation of a brain tumor.
