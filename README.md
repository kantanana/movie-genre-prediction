# Genre prediction

# Problem Statement
We aimed to attempt predicting the genre of the movie for people to be able to know whether it suits their taste:
1. Make informed decisions about their movie-to-watch
2. increase satisfaction from watching movie
3. make movies more worth watching

# Solution
- We have thereby come up with a machine learning model that predicts the genre based on image classification
- Leveraging historical movie data via the use of these features enables our model to provide an estimate of the movie genre based on the image
- movegoers can use this to find movie they may be interested in watching based on genre

# Role of AI (Machine Learning)
- AI in the form of a machine learning model plays a crucial role in our solution
- Training a machine learning model on a dataset of historical movie data enables us to capture patterns and relationships between movie features and genre
- This trained model can then be used to predict the popularity of new movies based on previously mentioned pointers
- Via leveraging data-driven insights, this could help us to make accurate predictions, providing valuable insight for moviegoers

# Reason for model chosen
- VGG16 is a pre-trained convolutional neural network (CNN) model trained on a large dataset, which enables transfer learning
- VGG16 has shown high accuracy on image classification tasks, making it a reliable choice
- With its 16-layer structure, VGG16 can capture both low-level features and high-level semantic concepts in movie images
- VGG16 is readily available in popular deep learning frameworks, simplifying implementation.
- By leveraging VGG16's pre-trained weights and adding custom layers, the code benefits from its learned representations and generalization capabilities.

