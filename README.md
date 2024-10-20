# DeepLearningPyTorch
Project for the online course [Deep Learning with PyTorch](https://jovian.com/learn/deep-learning-with-pytorch-zero-to-gans) at [Jovian](https://jovian.com). It can be run on Google Colab or Kaggle. In this project, I use a [Kaggle dataset](https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset) of pets' emotions to classify the differential emotions of pets' across 7 species. I mainly use the various functions of `torch` and `torchvision` packages.

In this project, I do the following.
- Download the dataset.
- Perform exploratory data analysis to obtain basic information about the dataset: number of images and classes, shape of the images. In this case, the training set has 1000 images of 4 classes.
- Perform augmentation (padding, crop, flip) and channel normalization to add more variation of the data.
- Train the model using transfer learning with a CNN model `ResNet50`.
- Tune hyperparameters: number of epochs, learning rate, achieveing 55.56% validation accuracy score.
- Make predictions, achieving 80% accuracy of the test set for the Angry emotion class.

