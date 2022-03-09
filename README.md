This document will help you understand how to use this program

First of all, if you want to run in colab, you need to modify the following path

You need to upload your dataset files to colab's cloud drive in the form of a folder
Then find the path of the folder, replace the following path, make sure it is the folder where the five datasets are located

For example, my dataset is in the bbc folder, I need to copy the path of the bbc folder and replace the part in quotation marks in the following path
root=r"/content/drive/MyDrive/news_classifacation/bbc"

The datasets used by this program are txt files, which are placed in five folders. The datasets have no labels. If you need to replace the datasets, please ensure that the format and storage method are the same as the datasets used by this program.
Then run each code block in turn to complete the processing and classification of the dataset


If you want to run the program in the terminal, then you need to modify the path to the absolute path of your dataset decompression folder

For example, my dataset's absolute path is D:\python project\machine_learning_coursework\bbc\dataset,then i need to copy it and replace the path in the quotation mark
root=r"/content/drive/MyDrive/news_classifacation/bbc"

Also, you don't need the following library references
from google.colab import drive
drive.mount('/content/drive')
