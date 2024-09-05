# CXR

A chest X-Ray learning app.

## Note/Warning

[Data limitations](https://www.kaggle.com/datasets/nih-chest-xrays/data):

> "The image labels are NLP (natural language processing) extracted so there could be some erroneous labels but the NLP labelling accuracy is estimated to be >90%."

As the interpretation of the data is not 100% accurate, there could be cases of incorrect data, such as inaccurately labelled chest X-rays, false positives, false negatives, correctly labeling but missing other diseases in the labeling, etc.

## Data

[Original data provider: NIH Clinical Center](https://nihcc.app.box.com/v/ChestXray-NIHCC)

[Data downloaded for this app: Kaggle/nih-chest-xrays](https://www.kaggle.com/datasets/nih-chest-xrays/data)

[CVPR 2017 paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)

[CVPR 2017 paper in arXiv](https://arxiv.org/pdf/1705.02315)

Citation:

> Xiaosong Wang, Yifan Peng, Le Lu, Zhiyong Lu, Mohammadhadi Bagheri, Ronald Summers, ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases, IEEE CVPR, pp. 3462-3471, 2017

## Changes in the app

The original data included cases that weren't labelled with any lung diseases; these were removed in the app. All chest X-ray images shown in the app have at least one lung disease labelled.

Result: 50,000+ chest X-ray images from 30,000+ unique patients.

## Privacy Policy

[Privacy Policy](privacy-policy.md)

## Support

If you need assistance, have questions, or would like to provide feedback to the author, please send an email:

- Email: gimbapapps@gmail.com
