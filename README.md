# ML_CNN_ImgClass_PyTorch
 
Classify images using CNN (Convolutinoal Neural Network)

Dependencies: numpy, torch (PyTorch), torchvision

Data sets: CIFAR10

Data :60000 32x32 colour images in 10 classes, with 6000 images per class(50000 training images and 10000 test images)
Categories : airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck

Structure: CONV-ReLU-CONV-ReLU-CONV-ReLU-CONV-ReLU-CONV-ReLU-Max Pooling-Batch Norm-FC(fully-connected)

Hyperparameter setting
- epoch =15
- lr = 1e-3
- batch_size = 64
- optimizer =  Adam
- loss = CrossEntropyLoss

Result: Training accuracy: 80.49600219726562, Testing accuracy: 65.4800033569336

*MEMO: Google colab notebook
