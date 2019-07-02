# Breast-Cancer-Detection
#create an account on Kaggle’s website to download the dataset.
in the dataset there are two types of images.These images are separated into either benign ( 0/ ) or malignant ( 1/ ) directories

#project structure ....................
├── datasets
│   └── orig
│       ├── 10253
│       │   ├── 0
│       │   └── 1
│       ├── 10254
│       │   ├── 0
│       │   └── 1
│       ├── 10255
│       │   ├── 0
│       │   └── 1
...[omitting similar folders]
│       ├── 9381
│       │   ├── 0
│       │   └── 1
│       ├── 9382
│       │   ├── 0
│       │   └── 1
│       ├── 9383
│       │   ├── 0
│       │   └── 1
│       └── IDC_regular_ps50_idx5.zip
├── main
|   |--_pycache_
|       |--__init__.cpython-36
|       |--cancernet.cpython-36
|       |--config.cpython-36
│   ├── __init__.py
│   ├── config.py
│   └── cancernet.py
├── build_dataset.py
├── train_model.py
|---load model.py
|--saved_model.model
└── plot.png

   # config.py : Contains our configuration that will be used by both our dataset builder and model trainer.
   #build_dataset.py : Builds our dataset by splitting images into training, validation, and testing sets.
   #cancernet.py : Contains our CancerNet breast cancer classification CNN.
   #train_model.py : Responsible for training and evaluating our Keras breast cancer classification model.
   #saved_model.model: it is the output of the train_model.py .it is a model to to classify the images.
   #load_model.py:  it take the file saved_model.model and take a folder of images and give the output in 4X4 image popup window 
   with classification of images.
   
  
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
