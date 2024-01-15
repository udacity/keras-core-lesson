# Are You Looking At The Road

In this exercise, you will learn how to use transfer learning to predict the direction a person is facing while driving, with the context of determining if the driver is looking at the road. There are four possible directions: left, right, up, and straight. You will use a pre-trained convolutional neural network (CNN) model as a feature extractor and implement a classification model using Python and Multi-backend Keras.

## Folder Structure

```
Exercise2-are-you-looking-at-the-road
    |_ solution
    |   |_ face-direction-classification.ipynb
    |_ starter
    |   |_ face-direction-classification-starter.ipynb
    |_ face-direction-dataset
    |   |_ left
    |   |_ right
    |   |_ straight
    |   |_ up
    |_ README.md
```

- `face-direction-classification.ipynb`: This notebook contains the solution for the face direction classification exercise. It goes through how to download a pre-trained model, and repurpose it with additional layers for a new task.
- `face-direction-classification-starter.ipynb`: This notebook contains the starter code for the face direction classification exercise. It provides a structured environment for you to work on the exercise step by step.
- `face-direction-dataset`: The dataset that you will working on. We have organised it for you into four folders (`left`, `right`, `up` and `straight`) for the respective classes.
