
# Skin Lesion Classification

This repository contains the implementation of the **Skin Lesion Classification** project, designed to classify medical images of skin lesions. This project employs an ensemble of **LightGBM**, **CatBoost**, and **EfficientNet-B0** models, with advanced preprocessing and feature engineering techniques to enhance classification performance.

## Features

- **Model Ensemble**: Combines the strengths of LightGBM, CatBoost, and EfficientNet-B0 for improved accuracy.
- **GeM Pooling**: Implemented Generalized Mean Pooling for large-scale image datasets.
- **Feature Engineering**: Engineered 20+ features for the model.
- **Advanced Preprocessing**: Applied various preprocessing techniques on medical images, including resizing, normalization, and augmentation.

## Datasets

- **Skin Lesion Dataset**: Publicly available medical image dataset consisting of skin lesion images. Please refer to the official dataset source for download instructions.

## Model Architecture

- **EfficientNet-B0**: Pre-trained convolutional neural network fine-tuned for the task of skin lesion classification.
- **LightGBM** & **CatBoost**: Gradient boosting models used for tabular feature classification, forming part of the ensemble.

## Results

- **Accuracy**: Achieved high classification accuracy on the validation set.
- **Benchmarking**: Performance evaluated on key metrics like precision, recall, and F1-score.

## Installation

To set up the environment and run the project:

```bash
git clone https://github.com/heyyviv/Skin-Lesion-Classification.git
cd Skin-Lesion-Classification
pip install -r requirements.txt
```



## Running Notebooks on Kaggle

To run the project notebooks, you can access them on my Kaggle profile:
[Kaggle Profile - heyviv](https://www.kaggle.com/heyviv)

## Future Work

- **Model Improvements**: Explore other architectures like EfficientNet-V2 or Transformer-based models.
- **Data Augmentation**: Experiment with advanced augmentation techniques to further improve performance.
- **Deployment**: Plan to deploy the classification model using Streamlit or Flask for real-time predictions.

## Contributing

Contributions are welcome! Please fork the repository, submit a pull request, and ensure detailed documentation of any changes.

## License

This project is licensed under the MIT License.
