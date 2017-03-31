# NSLKDD-Dataset
NSL-KDD Dataset for WEKA - feel free to download

Original dataset with slight modification to include attack categories e.g. DOS, U2R as done with the original Kdd99 dataset.
Features: All attacks divided and use real-values.

Attacks were assigned with real values in new field called xAttack:

dos = [1]

u2r = [2]

r2l = [3]

probe = [4]

normal = [5]

unknown = [6]

After each dataset was divided the xAttack field was reworked for binary classification e.g. 0;1. 0 = normal traffic, 1 = malicous traffic.

The datasets have also been coded, the following fields' flag, service and protocol_type categories now represents numerical values instead of categorical. 

Please contact me if you require multi-class classification on the NSL-KDD dataset based on the xAttack field. Please contact me if you require any assistance to prepare data for your algorithm or pre-processing.

Please reference this github for any usage within your research.

