# Deep Learning - Furniture & Home Goods Recognition

![alt text](https://cdn-images.article.com/products/SKU343A/2890x1500/image38120.jpg?w=2890)

As shoppers move online, it’d be a dream come true to online stores to have products in photos classified automatically. But, automatic product recognition is challenging because, for the same product, a picture can be taken in many different ways. This project aims to end with this problem by developing an algorithm that will help online stores move towards automatic product recognition and accurately assign category labels for furniture and home goods images.

## Transfer Learning

The project leverages the power of transfer learning to use the weights and architecture of two models that has been previously trained in millions of images. These two models are VGG-16 and InceptionV3.

![alt text](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/05/31130754/transfer-learning.jpeg)


## Project Findings
[Project Description & Code](https://github.com/joaobecker/deep_learning_furniture/blob/master/furniture_caps.ipynb)

## Data
The project will be using the data available from the Kaggle competition - [iMaterialist Challenge (Furniture) at FGVC5](https://www.kaggle.com/c/imaterialist-challenge-furniture-2018/data)

## Results

By leveraging transfer learning from VGG-16 model as feature extractor to our model, we achieved an impressive result of 93.6% accuracy and 85% validation accuracy, even though we only had a total of 3’699 images available in our dataset. Thus, helping online stores automate product recognition with high accuracy and making them more efficient. 


![Screenshot of Brave Browser (2019-03-15, 9-52-13 AM)](https://user-images.githubusercontent.com/31840058/54448873-00ca1700-470a-11e9-9b38-898ed2172f7e.png)

![Screenshot of Brave Browser (2019-03-15, 10-20-57 AM)](https://user-images.githubusercontent.com/31840058/54449748-13dde680-470c-11e9-8ed5-788dc1a749a4.png)

## Next steps

I would like to use this algorithm to create an app to find your dream furniture & home goods, for cheaper!

The app would only need an input of a single picture of your dream furniture, then it would use the algorithm created in this project to recognize which category it falls into and use a clustering algorithm to find cheaper, similar products.

If you are interested in helping me out with this project, let me know! :D


