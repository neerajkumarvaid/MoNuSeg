# [MoNuSeg challenge](https://monuseg.grand-challenge.org/) organized at [Miccai 2018](https://www.miccai2018.org/en/)

Please cite the following paper if you use this repository-
[Kumar, N., Verma, R., Sharma, S., Bhargava, S., Vahadane, A., & Sethi, A. (2017). A dataset and a technique for generalized nuclear segmentation for computational pathology. IEEE transactions on medical imaging, 36(7), 1550-1560](https://ieeexplore.ieee.org/document/7872382)



| **File name** | **Description** |
| ------------- | ------------- |
| [compute_AJI](https://github.com/RuchikaVermaVaid/MoNuSeg/blob/master/compute_AJI.m) | Compute average AJI across all nuclei for each image|
| [Ensemble_mask](https://github.com/ruchikavermavaid/MoNuSeg/blob/master/ensemble_top_5.m) | Combine instance masks of top 5 techniques to get ensemble mask using majority voting|
| [correct_nd_missing_nuc_count](https://github.com/RuchikaVermaVaid/MoNuSeg/blob/master/correct_nd_missing_nuc_count.m) | Count correctly classified nuclei and missing nuclei in each predicted mask of top 5 techniques|
| [he_to_binary_mask_final](https://github.com/ruchikavermavaid/MoNuSeg/blob/master/he_to_binary_mask_final.m) | Use H&E stained image along with associated xml file to generate binary and colored mask|

