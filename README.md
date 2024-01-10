# Dogs vs. Cats Redux: Kernels Edition (Kaggle Competition)

The primary objective of this Kaggle competition is to predict whether an image features a dog or a cat. 
For more details, visit https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/overview


## Dataset

The training data comprises 25,000 images of dogs and cats, with labels embedded in filenames. The test set has 12,500 images identified by numeric IDs. The challenge is to predict the probability of an image being a dog (1 = dog, 0 = cat).

## Predictive Models

Experimentation involved three pre-trained models for binary classification:

1. VGG16
2. ResNet50
3. Xception

## Final Results

Kaggle Score
- VGG16 Model: 0.1667
- ResNet50 Model:0.17
- Xception Model: 0.07509 (Best Result)

The Xception model demonstrated superior performance with the lowest Kaggle score of 0.07509 among the three models. This result indicates the effectiveness of the Xception architecture for this specific classification task. Further details and code can be found in the project repository.
