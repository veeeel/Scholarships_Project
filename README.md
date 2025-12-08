# Emotion Recognition
Team H4

Authors: Jaanika Seli, Mattis Vrager, Sandra-Liis Mägi

## Motivation and goal
* Predict emotions based on facial expressions with ≥80% accuracy across five classes: happy, sad, angry, afraid, surprised
* Identify the best-performing classifier for this task
* Determine which emotions are most difficult for models to distinguish
* Gain deeper understanding of Convolutional Neural Networks and image recognition

## Guide to the contents of the repository

```
SCHOLARSHIPS_PROJECT/
│
├── human-face-emotions/         # Dataset folder (images grouped by emotion) - Must be downloaded by user
│
├── models/                      # Saved trained models (.keras)
│
├── training_history/            # Saved training histories (.pkl)
│
├── visuals/                     # Plots and figures used in the poster/report
│
├── .gitignore                   # Ignore image data
│
├── CNN_aug.ipynb                # CNN with data augmentation experiments
├── CNN_baseline_and_resnet.ipynb# Shallow CNN + Mini-ResNet experiments
├── CNN_og.ipynb                 # Best performing self-built CNN + some analysis and visualization
├── CNN_transfer_learning.ipynb  # MobileNetV2 transfer learning + some analysis and visualization
├── Transformer.ipynb            # Small self-trained visual transformer
│
├── model_comparison.ipynb       # Unified evaluation plots
│
├── H4_report.pdf                # Homework 10
├── plan.txt                     # Early project planning notes
├── prep_data.ipynb              # Must be ran first - loading and cleaning the dataset
└── README.md                    # Project overview and instructions
```

## How to run the code
1. Clone this repository: https://github.com/veeeel/Emotions_project.git
2. Run the notebook prep_data.ipynb - this loads the dataset from Kaggle into the repository. For this to work, computer must have a unique kaggle.json file downloaded (from here: https://www.kaggle.com/datasets/samithsachidanandan/human-face-emotions/data) and the file must have this path: "C:\Users\youruser\.kaggle\kaggle.json". In this notebook also is performed cleaning of data - we got rid of images that contained full body or multiple people. For this we used a robust method of removing all images exceeding 48x48 size, as that's where the non-uniform images were.
3. Run any of the model training notebooks. There the trained models and training histories can be saved into folders 'models' and 'training_history' using existing code.
4. Run the model_comparison.ipynb notebook. For this to work, the training histories of models must be saved in 'training_history' folder.




