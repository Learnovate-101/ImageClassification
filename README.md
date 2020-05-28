# ImageClassification
CIFAR-10 Dataset Image classification using Convolutional Neural Networks with Keras.
Clone or Download the repo and run it in Jupyter.
Dataset will be downloaded directly while running the cell [3], you need an active Internet connection for downloading the 170 mb dataset.
I have used only three classes (i.e. aeroplane car and bird) among the 10 classes present in cifar-10.
Model runs for 20 epochs but I have used callbacks and patience(=2) for optimised results.
Best model has loss: 0.0824, accuracy: 0.9685, val_loss: 0.2712, val_accuracy: 0.9157. (Results differ for every person and even every run).
Also you can load and save the best performing model and use it later for results accordingly.
For CNN:- Total params: 289,443, Trainable params: 288,995, Non-trainable params: 448

{ p.s. for any error or support feel free to ask } 
