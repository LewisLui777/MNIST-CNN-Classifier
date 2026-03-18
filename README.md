Project Overview: For our project, we wanted to explore how variations in model architecture and hyperparameters can affect a CNN's ability to correctly classify images in the MNIST dataset.

Setup Instructions: Please download the Python file and simply run it in an editor like VS Code.

Required Dependencies: The file requires torch, torchvision, and matplotlib to properly function.

How to train the model: The code file will automatically train the models when you run it, although the more specific answer is you run train_model or train_model_hinge with the appropriate arguments.

How to evaluate the model: The code file will automatically evaluate the models' accuracies when you run it, although the more specific answer is you run test_model with the appropriate arguments.

Expected Outputs: The file will ideally output 12 graphs that show each model's accuracy over the entire training process. Beneath each graph, it will state the model name, the activation function used, the loss function used, the learning rate used, and the test accuracy.

Where to download the dataset: Call the download_training_dataset and download_testing_dataset methods with your desired batch sizes. More specifically, you can call torchvision.datasets.MNIST with arguments to retrieve the full dataset. 

How to preprocess the data: Our download_training_dataset and download_testing_dataset methods will automatically preprocess the data for you, although the specific method is that we transform the data into tensor form using .ToTensor() and then normalize using .Normalize.

How to reproduce your results: Simply run our Python file and the 12 graphs along with their corresponding metadata should show up in your editor terminal. 

Sample Dataset: The MNIST dataset is public and should be available for access by anybody.

Demo notebook: https://colab.research.google.com/drive/1WMjtERUh1HUCQ95GGeNdaVkm-yedSs24#scrollTo=4YEoFo2mafzJ

