# Lab 3

```bash
├── data 
    └── cl
        └── valid.h5        # this is clean validation data used to design the defense
        └── test.h5         # this is clean test data used to evaluate the BadNet
    └── bd
        └── bd_valid.h5     # this is sunglasses poisoned validation data
        └── bd_test.h5      # this is sunglasses poisoned test data
├── models
    └── bd_net.h5
    └── bd_weights.h5
    └── repaired_2.h5       # B' for X = 2%
    └── repaired_4.h5       # B' for X = 4%
    └── repaired_10.h5      # B' for X = 10%
├── architecture.py
├── ML_Security_Report.pdf  # pdf version of main.ipynb
├── main.ipynb              # this is colab notebook for lab3
└── eval.py                 # this is the evaluation script
```

## Steps to execute
   1. Download the datasets from [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq?usp=sharing) and store them under `data/` directory.
   2. Follow the steps in [main.ipynb](https://github.com/superChoi7/ML_for_Cyber_Lab3/blob/main/main.ipynb) to execute the notebook.
   3. You can find the pdf version of notebook [here](https://github.com/superChoi7/ML_for_Cyber_Lab3/blob/main/ML_Security_HW3.pdf).
