# MNIST
This program aims to classify MNIST dataset using neural networks. This work includes two neural networks, first one using only a deep neural network, and second one using Convolutional neural network.
<br/>
![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/4a94aade-63fc-4fa0-9677-f4dc6221cd11)<br/>
The MNIST dataset contains hand-written digits, and the program tries to classify the input into 10 classes.
<br/>
![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/45ad1de4-77a6-4289-8597-e2e4a7c739ed)<br/>
At last, it aims to classify an unseen data(test data).
## MNIST without CNN
This version implements neural network without use of a convolutional layer. The pixel intensities are fed into deep neural network, and the model outputs the corresponding class(digit) of the input.<br/>

![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/8068014b-95e4-441c-b46b-44884e255ca8)
![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/7b064dc2-64fb-4738-9328-f0be6596ad28)
The blue line represents the training set, and the orange line the validation set.<br/>

## MNIST with CNN
This version incorporates convolutional layers into our neural network. Lenet Model has been used and following results show that our model's performance has increased.<br/>
![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/e90f46d3-5553-4ce1-9ee0-57b53c31831f)
![](https://github.com/Rietchie0119/Lane-detection/assets/28763133/916d1db7-5f7a-4a97-b1e4-037265ae65c7)
