ES-335 ASSIGNMENT 4 under Prof.Nipun Batra 

1. In this question, you have to compare the performance on a binary classification task of the following models: 

    - VGG (1 block) 
    - VGG (3 blocks)
    - VGG (3 blocks) with data augmentation
    - Transfer learning using VGG16 or VGG19 with tuning all layers (including tuning convolution layers)
    - Transfer learning using VGG16 or VGG19 with tuning only final MLP layers (excluding convolution layers)

    
    [Refer this article](https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-photos-of-dogs-and-cats/)  
    
    You need to create the dataset on your own based on your first names of any two members from the group. For instance if the first name of the team members are: **V**aidehi and **R**aghav, they can choose a dataset of their liking based on any names, place, animal or thing. As examples:

    - Vulture v/s Rat
    - Vada Pav v/s Roti

     You can refer to [resource 1](https://python.plainenglish.io/how-to-automatically-download-bulk-images-for-your-dataset-using-python-f1efffba7a03) or [resource 2](https://github.com/JorgePoblete/DuckDuckGoImages) or plainly download 100 images of both classes (total 200 images). Of these 100 images of each class, we will use 80 for training and 20 for testing.
     
     
     Create a table with models as rows and the following columns 

    - Training time
    - Training loss
    - Training accuracy
    - Testing accuracy
    - Number of model parameters



    We will now be using Tensorboard for visualising network performance. You are suggested to refer to:

    - [PyTorch + Tensorboard](https://www.youtube.com/watch?v=RLqsxWaQdHE)
    - [Tensorflow + Tensorboard](https://www.youtube.com/watch?v=k7KfYXXrOj0)

    
    Use Tensorboard to log the following and present screenshots/images
    

    Scalars
    - Training loss v/s iterations (and not epochs)
    - Training accuracy v/s iterations (and not epochs)
    - Testing accuracy v/s iterations (and not epochs)

    Images
    - Show all images from the test set and their predictions


    Now you have to present various insights. For instance, you should discuss the following: 

    - Are the results as expected? Why or why not?
    - Does data augmentation help? Why or why not?
    - Does it matter how many epochs you fine-tune the model? Why or why not?
    - Are there any particular images that the model is confused about? Why or why not?
    

    Now, create an MLP model with parameters comparable to VGG16 and compare your performance with the other models in the table. You can choose the distribution of the number of neurons and the number of layers. What can you conclude?
