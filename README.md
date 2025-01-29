from google.colab import drive
drive.mount('/content/drive')

import numpy as np
import pandas as pd
train = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/ML EXCERCISES/train2.csv").set_index("id")
test = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/ML EXCERCISES/test2.csv").set_index("id")
