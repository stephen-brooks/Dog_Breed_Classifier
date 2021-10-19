# Udacity Dog Breed Classifier Project using Pytorch.
## Project Design

1. Import necessary datasets and libraries, split datasets into train, validation and test. Pre-process data as required for each model
2. Import pre-trained Haar classifier and use to detect humans in datasets
3. Import pre-trained VGG16 model and use to detect dogs in datasets
4. Create a CNN classifier from scratch and justify your choice of model architecture
5. Decide on pre-trained model, once trained, test accuracy and loss
6. Use models trained in previous steps to write algorithm that tests firstly for the presence of a dog, returning the breed if true. If a dog is not detected, the model will check for human features. If human features are present, then return what breed the human looks like, otherwise, return an error
