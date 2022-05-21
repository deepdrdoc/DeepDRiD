# Deep-Diabetic-Retinopathy-Image-Dataset-(DeepDRiD)
* ISBI-2020 Challenge 5: Diabetic Retinopathy Assessment Grading and Diagnosis (AM Session)

* Abstract: 
* Automated machine learning can facilitate the early diagnosis and timely treatment of diabetic retinopathy. Following the 1st Diabetic Retinopathy: Segmentation and Grading Challenge held with ISBI in 2018, we would like to promote the progress further through 2nd challenge using a new dataset, Deep Diabetic Retinopathy Image Dataset (DeepDRiD). The challenge is subdivided into three tasks as follows:
    * A. Dual-View Disease Grading: Classification of fundus images according to the severity level of diabetic retinopathy using dual view retinal fundus images.
    * B. Image Quality Estimation: Fundus quality assessment for overall image quality, artifacts, clarity, and field definition.
    * C. Transfer Learning: Explore the generalizability of a Diabetic Retinopathy (DR) grading system. The robust and generalizable models are expected to be developed to solve clinical issues in reality.

* In the 2020 ISBI competition, we organized three sub-challenges based on the above tasks. After the online competition, many researchers are still very concerned about obtaining our dataset and further research. We published the training, validation, and external validation data involved in the ISBI competition on this Github repository for further research to facilitate research on DR grading, DR image quality analysis, and ultra-wide image transferring.
* The file structure of the DeepDRiD dataset is as follows:
```
.
├── regular_fundus_images
│   ├── Online-Challenge1&2-Evaluation
│   │   ├── Challenge1_upload.csv
│   │   ├── Challenge2_upload.csv
│   │   ├── Images
│   │   └── Readme.docx
│   ├── regular-fundus-training
│   │   ├── Images
│   │   ├── Readme.docx
│   │   └── regular-fundus-training.csv
│   └── regular-fundus-validation
│       ├── Images
│       ├── Readme.docx
│       └── regular-fundus-validation.csv
└── ultra-widefield_images
    ├── Online-Challenge3-Evaluation
    │   ├── Challenge3_upload.csv
    │   ├── Images
    │   └── Readme.docx
    ├── ultra-widefield-training
    │   ├── Images
    │   ├── Readme.txt
    │   └── ultra-widefield-training.csv
    └── ultra-widefield-validation
        ├── Images
        ├── Readme.txt
        └── ultra-widefield-validation.csv
```

* In sub-challenge 1&2, the labelled training dataset is given by `regular-fundus-training`, and the details of the label are shown in the `Readme.docx` file. The labelled validation dataset is given by `regular-fundus-validation`, the structure is the same as the training fold. Also, we gave our external dataset in `Online-Challenge1&2-Evaluation` which is unlabeled.
* In sub-challenge 3, we gave the ultra-wide fundus images for transfer learning. The structure of ultra-wide fundus images is the same as regular fundus images.


****************************UPDATE: April 7th***************************************
We provide the source of each image in regular fundus. All regular fundus are in three studies: Niching Diabetes Screening Project\Shanghai Diabetic Complication Screening Project\Nationwide Screening for Complications of Diabetes. In the added file, we used "Nicheng" to represent Niching Diabetes Screening Project, "Shanghai" to represent Shanghai Diabetic Complication Screening Project, and "Nation" to represent Nationwide Screening for Complications of Diabetes.

# Citation
If you use this dataset for your research, please cite our paper:
```bib
@article{LIU2022100512,
title = {DeepDRiD: Diabetic Retinopathy—Grading and Image Quality Estimation Challenge},
journal = {Patterns},
pages = {100512},
year = {2022},
issn = {2666-3899},
doi = {https://doi.org/10.1016/j.patter.2022.100512},
url = {https://www.sciencedirect.com/science/article/pii/S2666389922001040},
author = {Ruhan Liu and Xiangning Wang and Qiang Wu and Ling Dai and Xi Fang and Tao Yan and Jaemin Son and Shiqi Tang and Jiang Li and Zijian Gao and Adrian Galdran and J.M. Poorneshwaran and Hao Liu and Jie Wang and Yerui Chen and Prasanna Porwal and Gavin Siew {Wei Tan} and Xiaokang Yang and Chao Dai and Haitao Song and Mingang Chen and Huating Li and Weiping Jia and Dinggang Shen and Bin Sheng and Ping Zhang},
keywords = {diabetic retinopathy, screening, deep learning, artificial intelligence, challenge, retinal image, image quality analysis, ultra-widefield, fundus image},
}
```
