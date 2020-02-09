This project aims at real-time recognition of hand gestures to communicate with other devices by producing words and commands using sequence of hand signs.
The dataset used is MNIST sign data from Kaggle and entire detail about the dataset can be found at .

The notebook SignLanguage learning aims at developing CNN model for learning had signs from the given pixel information. Each input image is 28x28 gray image.

for the test purpose 3 models were developed with different convolution mask and pooling parameters.

All parameters were choosen with aim of using the model in real time using CPU and hence the complexity of the following dense NN was rather sparse.

The notebook "Test Models" aims at testing the models using OpenCV and can be used readily if the models are saved in the same folder.

