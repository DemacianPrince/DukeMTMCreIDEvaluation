# DukeMTMC-reID Evaluation Code
Matlab codes for evaluating performance on [DukeMTMC-reID Dataset](https://github.com/layumi/DukeMTMC-reID_evaluation).

### Usage
1. Calculate and save the feature for the query and gallery images of the dataset in advance;

2. Change the query and gallery feature directory in the codes correspondingly;

3. Run `duke_evaluation.m` to get the Rank1-Accuracy and mAP result.

### Citation
If you use this code, please kindly cite this paper:

     @inproceedings{zheng2015scalable,
       title={Scalable Person Re-identification: A Benchmark},
       author={Zheng, Liang and Shen, Liyue and Tian, Lu and Wang, Shengjin and Wang, Jingdong and Tian, Qi},
       booktitle={Computer Vision, IEEE International Conference on},
       year={2015}
     }
