# Cricket-Image-Caption-Generator

Cricket image caption generator, generates meaningful descriptions for a given cricket image.
#### Dataset
For this project, we have used two datasets.
1.	Flickr8k Dataset from Kaggle
2.	Custom Dataset
We used Flickr8k Dataset to understand the code and custom dataset to implement the same idea on the dataset of our interest
This particular dataset was created by us. Here we have concentrated on selecting images from one particular domain – Sports, co-domain – Cricket.
Our dataset consists of 581 “.jpg” images that are paired with their corresponding captions which provide a description of the salient features
The images were downloaded from Google and were manually selected to depict a variety of scenes and situations. Each of the 581 images was captioned manually.
This dataset also contains two files, one containing all the “.jpg” cricket images and the other containing the corresponding image captions in “.txt” file format.

#### Methodology
In this project, we have built an image caption generator to load a random cricket image and give some captions describing the image. We have used Convolutional Neural Network (CNN) for image feature extraction, Long Short-Term Memory Network (LSTM) for Natural Language Processing (NLP), and BLEU to test the accuracy of the generated caption.


Output for one of the image
![image](https://user-images.githubusercontent.com/103937074/236610341-77459fc8-6a0e-42bd-becc-0bfb44b98cec.png)

Done by
Sarvesh
Franklin
Vaishnavi Sudakar
Nandha
Jaswanth
Harshitha
