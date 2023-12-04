The below structure and file is available in my Google Drive **(https://drive.google.com/drive/folders/1u9WR8cQA12ilJEgNp6ZgHsaXF0UtA8mS?usp=drive_link)** which has been taken from the provided Github Link: **(https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3)**
**Lab 3**
```bash
├── MLHW
└── cl
        └── valid.h5 // this is clean validation data used to design the defense
        └── test.h5  // this is clean test data used to evaluate the BadNet
└── bd
        └── bd_valid.h5 // this is sunglasses poisoned validation data
        └── bd_test.h5  // this is sunglasses poisoned test data
├── models
    └── sunglasses_bd_net.h5
    └── sunglasses_bd_weights.h5
```


**Dependencies**
Python 3.6.9
Keras 2.3.1
Numpy 1.16.3
Matplotlib 2.2.2
H5py 2.9.0
TensorFlow-gpu 1.15.2

**Instructions on running the code -**
- Make sure that there is enough memory available for the execution (Ideally, Google Colab Pro subscription would do)
- The data set can be available from the links mentioned **(https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3)** and the Google drive link to the data files is **(https://drive.google.com/drive/folders/1u9WR8cQA12ilJEgNp6ZgHsaXF0UtA8mS?usp=drive_link)**

To evaluate the backdoored model, run the 1st cell of the code file **'ds6969.ipynb'** which is exact of 'eval.py' file of the Github Link.

There is a report **(ML_HW_Doc)** also attached  that includes a table with the accuracy of clean test data and the attack success rate (on backdoored test data) as a function of the fraction of channels pruned (X).


