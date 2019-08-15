## Kaggle-Competition-Digit-MNIST-Simplified-ResNetV1-acc0.995

https://www.kaggle.com/patricksu/minst-simplified-resnet-v2

- This for practicing Model functional API in Keras which can build more complicated model compared to Sequential one.
Model was modified from ResNetV1 with fewer layers, and it can save training time.

- Learning rate decay was used to further enhance the accuracy because when it reached above 0.992, it can be 
difficult to improve with same training strategy. Also, extra SGD method was applied to anneal the loss, and
prevent it goes too fast by using Adam.

- Training and testing data can be found on Kaggle 
https://www.kaggle.com/c/digit-recognizer/data
