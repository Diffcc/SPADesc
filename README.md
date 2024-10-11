# SPADesc

# Requirement
To use SPADesc, ensure you have:

* Python 3.8 or higher
*  Dependencies listed in requirements.txt

Install dependencies via:
```
pip install -r requirements.txt
```

# Data Preparation
We use MegaDepth for training, please refer to the dataset settings in [AWDesc](https://github.com/vignywang/AWDesc/tree/main) for details. 

# Training
Training code for SPADesc will be provided in a future release. 

# Testing

**HPatches Image Matching Benchmark
**
```
cd evaluation_hpatch/hpatches_sequences
jupyter-notebook

run HPatches-Sequences-Matching-Benchmark.ipynb
```
![image](https://github.com/user-attachments/assets/10a021d0-4986-4e5d-bb30-96e7b0af0041)


**Visual Localization Benchmark
**
Follow the [image-matching-toolbox](https://github.com/GrumpyZhou/image-matching-toolbox?tab=readme-ov-file) for details.

Upload the result file to [Long-term Visual Localization](https://www.visuallocalization.net/benchmark/), and you will receive the following result:

![image](https://github.com/user-attachments/assets/bffd2583-bab2-4704-b584-1a0e5d8591ad)


![image](https://github.com/user-attachments/assets/2c880661-4e2b-47ba-b561-f1f696dd926b)
