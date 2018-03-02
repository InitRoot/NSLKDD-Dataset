# NSLKDD-Dataset
NSL-KDD Dataset for WEKA - feel free to download

Original dataset with slight modification to include attack categories e.g. DOS, U2R as done with the original Kdd99 dataset.
Features: All attacks divided and use real-values. For more information on the feature coding process refer to http://scikit-learn.org/stable/modules/preprocessing.html#encoding-categorical-features

Attacks were assigned with real values in new field called xAttack:

dos = [1]

u2r = [2]

r2l = [3]

probe = [4]

normal = [5]

unknown = [6]

After each dataset was divided the xAttack field was reworked for binary classification e.g. 0;1. 0 = normal traffic, 1 = malicous traffic.

Validation dataset to be used for algorithm validation, Train20% split between 66% and 34% for validation.

The datasets have also been coded, the following fields' flag, service and protocol_type categories now represents numerical values instead of categorical. Feature selected datasets based on the research presented at ECCWS 2017 are denoted by FS in each folder.

Why use this dataset? Several researchers have claimed the NSL-KDD dataset is old, unrealistic and should not be used. This is facts, however it is crucial to keep the scope of your research project in mind. When you try to establish a methodology, algorithm or solution within the field, you have to provide comparitive results. Without such results the research cannot be compared and will not be as reproducible. However, you should also apply your solution towards a synthetic dataset afterwards and not constrain the project to only this dataset. 

Please contact me if you require multi-class classification on the NSL-KDD dataset based on the xAttack field. Please contact me if you require any assistance to prepare data for your algorithm or pre-processing.

Please reference this github for any usage within your research and the conference paper.

Botes, F., Leenen, L. and De La Harpe, R. (2017). Ant Colony Induced Decision Trees for Intrusion Detection. In: 16th European Conference on Cyber Warfare and Security. ACPI (June 12, 2017), pp.74-83.

```
@inproceedings{botes2017ant,
  title={Ant Colony Induced Decision Trees for Intrusion Detection},
  author={Botes, Frans and Leenen, Louise and De La Harpe, Retha},
  booktitle={16th European Conference on Cyber Warfare and Security},
  pages={53--62},
  year={2017},
  organization={ACPI}
}
```
https://www.researchgate.net/publication/318042231_Ant_Colony_Induced_Decision_Trees_for_Intrusion_Detection

Also please reference the original creators: 
```
References: [1] M. Tavallaee, E. Bagheri, W. Lu, and A. Ghorbani, “A Detailed Analysis of the KDD CUP 99 Data Set,” Submitted to Second IEEE Symposium on Computational Intelligence for Security and Defense Applications (CISDA), 2009.
```


