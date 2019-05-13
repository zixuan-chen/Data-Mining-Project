# Data-Mining-Project
Data-Mining-Project on Stock Price Prediction
## To run this project

1. Since the data file is to large to upload to github, you have to manually download it [here](https://www.kaggle.com/acviolet/stockpriceprediction/downloads/stockpriceprediction.zip/1) 

2. After download the dataset file(a single large file, around 1.63GB), you need to configure the `DATA_PATH` and `MODEL_PATH` on [parameter.py](https://github.com/m13953842591/Data-Mining-Project/blob/master/parameters.py). The `DATA_PATH` shows where your dataset is saved and the `MODEL_PATH` shows where your trained models is saved.

3. A single large dataset is not enough, we need to further process it to generate more valuable features. So you need to run the[ data_management.py](https://github.com/m13953842591/Data-Mining-Project/blob/master/data_management.py) to process the features. Note that you should configure the parameters of[ data_management.py](https://github.com/m13953842591/Data-Mining-Project/blob/master/data_management.py) on [parameter.py](https://github.com/m13953842591/Data-Mining-Project/blob/master/parameters.py)

4. just run the [train.py](https://github.com/m13953842591/Data-Mining-Project/blob/master/train.py) and you are ready!
