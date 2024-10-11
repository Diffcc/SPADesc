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

### HPatches Image Matching Benchmark

```
cd evaluation_hpatch/hpatches_sequences
jupyter-notebook

run HPatches-Sequences-Matching-Benchmark.ipynb
```
![image](https://github.com/user-attachments/assets/10a021d0-4986-4e5d-bb30-96e7b0af0041)


### Visual Localization Benchmark

Follow the [image-matching-toolbox](https://github.com/GrumpyZhou/image-matching-toolbox?tab=readme-ov-file) for details.

Upload the result file to [Long-term Visual Localization](https://www.visuallocalization.net/benchmark/), and you will receive the following result:

![image](https://github.com/user-attachments/assets/f131aca6-a78e-4e00-a994-51a5a15d0a43)


![image](https://github.com/user-attachments/assets/8cced2fc-699b-4fbd-b518-77710c61fc3b)

