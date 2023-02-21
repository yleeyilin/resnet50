# ComputerVision
ResNet 50 transfer learning on Oxford 102 Flowers Dataset 
Discriminative Learning Rates 

Discriminative learning rates refer to the use of different learning rates for different layers in a neural network. In the case of a pre-trained model, you can use a lower learning rate for the earlier layers, which have already been trained on a large dataset, and a higher learning rate for the later layers, which will be fine-tuned on the Flowers dataset. This can help the model converge faster and improve its performance.

To-do
1) Progressive Resizing: gradually increasing the size of the images used for training, chcks fine-grained details

Better Ways to evaluate the model's performance
1) F1 score 
