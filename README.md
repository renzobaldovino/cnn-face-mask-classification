# Face Mask Classification

In institutions where it is required to wear face masks, there are people who disregard the set regulations by not complying. 

The Face Mask Classification project was created to classify whether a person is wearing a face mask or not. This was done by creating a Convulational Neural Network Model that can accurately classify images of people that are wearing and not wearing face masks. The resulting model was used to classify people on a live video feed.

## Creating the CNN Model

The project was created by training a model with the __[Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)__ from kaggle. The dataset was first split into the train and test datasets using the `data-splitter.ipynb`. Afterwards, the CNN Model was created in the `cnn-model.ipynb` file. This was done by generating more images to train the model and using tested hyperparameters to increase its accuracy.

## Deploying the Model

After generating the CNN Model through the `cnn-model.ipynb` file, you can now detect face mask use live by running the `face-mask-classification.ipynb` file. This uses the computer's webcam feed and overlays filter indicating face mask use.

## How to run the Face mask Classification Project

1. Clone the repository.
2. Navigate to the cloned repository.
3. Download the __[Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)__ and place it in the repository.
4. Run the **`data-splitter.ipynb`** file to split the dataset into the training and testing dataset.
5. Run the **`cnn-model.ipynb`** file to create generate the CNN Model file.
6. Run the **`face-mask-classification.ipynb`** file to detect face mask use on a live video feed.
