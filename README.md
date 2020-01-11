# Bidirectional RNN Skeleton Training 
This repository contains, training on Skeleton Videos with Bidirectional RNN.

## PKU-MMD-V2

Download PKU-MMD-V2 dataset in http://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html
Copy the label files in pkuv2/data/label
Copy the skeleton files in pkuv2/data/skeleton
Copy the validation and training split files in pkuv2/data/split

- Execute pku_dataset python file. Thie file create PKUMMD h5py dataset.
- Execute various notebook file. (rl.pynb file not executable. In this file, video classification executable with reinforcement learning. This not executable.)