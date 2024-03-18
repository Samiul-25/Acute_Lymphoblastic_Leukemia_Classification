#It is Deep Learning based ALL Classification project which used ResNet50 model


Dataset Link :  https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class

Run File Process: 

1. Access and manipulate files in  Google Drive directly from  Colab notebook.
2. Use the Kaggle API in Colab notebook to download datasets in Kaggle from above dataset link.
3. ZIP file will be extracted in the current directory of Colab notebook.
4. Import tensorflow and numpy 
5. Dataset Load
6. Setting up a data augmentation pipeline using TensorFlow's Sequential API.
7. Build a transfer learning model using the ResNet50 architecture.
8. Create a visualization of this model.
9. Compiled this model using the categorical crossentropy loss, the Adam optimizer, and accuracy as the evaluation metric.
10.Train the model.
11.Visualize the training and validation loss as well as accuracy curves over epochs.
12.Evaluate the performance of the trained model.
13.Generate and visualize a confusion matrix using matplotlib and scikit-learn's confusion_matrix function.
14.Extract the true class label and the predicted class label using this trained model.
