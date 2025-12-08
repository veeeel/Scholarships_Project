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
├── approach2.ipynb              # Must be ran first - cleaning the dataset
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
└── README.md                    # Project overview and instructions
```

## How to run the code




