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
We use some data from MegaDepth for training, which can refer to the dataset settings in [AWDesc](https://github.com/vignywang/AWDesc/tree/main)

Training
Training code for SPADesc will be provided in a future release. Stay tuned for updates, including scripts to train models using semantic and parallel attention mechanisms.

Testing
Once trained, the model can be tested on new spatial data. Example:

python
复制代码
trained_model = spadesc.load_model("path_to_trained_model")
test_data = spadesc.load_data("path_to_test_data")
results = spadesc.test(trained_model, test_data)
spadesc.visualize(results)
