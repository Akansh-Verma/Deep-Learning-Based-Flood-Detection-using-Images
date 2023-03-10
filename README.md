# Deep Learning Based Flood Detection using Images

We propose flood detection in real-time with the help of multispectral pictures and SAR information the usage of Deep learning based Convolutional Neural network (CNN). Detection of ﬂood in real-time from the satellite images can be very beneficial for the disaster control authorities. The main purpose of this project is to offer a solution to detect ﬂood instead of predicting ﬂood, with the help of satellite snap shots that are freely available from many reliable assets. The trained model only desires a satellite image to hit upon the presence of ﬂood within the images. This system can also be used in area with water bodies to check the increase/decrease of water level in the area.

## Data

The dataset used for training and testing the model consists of satellite images of different regions. The images are annotated with labels indicating whether the area is prone to flooding or not. The dataset was sourced from various public repositories and cleaned for consistency.
[Dataset link](https://www.kaggle.com/datasets/saurabhshahane/roadway-flooding-image-dataset)

## Model

We have used a CNN model to train the flood detection model. The model takes in satellite images as input and outputs a probability score indicating the likelihood of flooding in the given area. The architecture of the CNN model consists of multiple convolutional layers followed by max-pooling and fully connected layers. The model has been trained on a GPU for faster processing.

## Results

The trained model has achieved an accuracy of 96% on the test set. It has also been tested on unseen data and has performed well in detecting flood-prone areas. The model can be further improved by increasing the size of the dataset and fine-tuning the hyperparameters.

## Usage

To use the trained model for flood detection, follow these steps:

1. Upload the code in you google colab project.
2. Mount the datset using this command 'drive.mount('/content/drive')'
3. The function will return a probability score indicating the likelihood of flooding in the given area.

## Contributing

Contributions to this project are welcome. If you find any issues or have any suggestions, please feel free to raise a pull request or open an issue.

## Contact information

You can contact through [Linkedin](https://www.linkedin.com/in/akansh-verma-205166213/).
