## covid-19 x-rey

This is a exercise for CNN. 
I use a small dataset for compare two models.
- First, a CNN model 
- Second, a transfer model(ResNet-V1)
### Dataset and ResNet model
You can access dataset with this [link](https://www.kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets). And the ResNet model is [here](https://tfhub.dev/google/imagenet/resnet_v1_101/classification/5).

### Result
##### CNN model 

> since this is a small dataset the model can't fit very well and goes to underfiting. I used image generator from TensorFlow to increase the data but it didn't help.
>
>GoogleColab [link](https://colab.research.google.com/github/matinkp/covid-19-x-rey-cnn/blob/main/x_rey_covid_19.ipynb)

##### Transfer learning

>sda
>
>GoogleColab [link](https://colab.research.google.com/github/matinkp/covid-19-x-rey-cnn/blob/main/x_rey_covid_19_transfer_learning.ipynb)
