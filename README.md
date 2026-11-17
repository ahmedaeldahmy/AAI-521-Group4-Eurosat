
# AAI-521 Group 4: Satellite Image Classification

## Project Overview

The project classifies satellite photos into 10 land types, such as forest, river, and residential.

EuroSAT has 27,000 small photos. The group uses one shared split so three models see the same train, validation, and test images. Ahmed’s Model A is a CNN built from scratch. Akua, Model B, is MobileNetV2 starting from ImageNet weights. Sai’s Model C is EfficientNetB0.

The goal is to compare which model is most accurate on the same test set and select that. 


**Course:** AAI-521 Applied Computer Vision for AI 
 
**Team:** Group 4

## Dataset

We will use the [EuroSAT RGB dataset](https://github.com/phelber/EuroSAT), which contains 27,000 Sentinel-2 satellite images across 10 categories:

- Annual Crop
- Forest
- Herbaceous Vegetation
- Highway
- Industrial
- Pasture
- Permanent Crop
- Residential
- River
- Sea/Lake

The images will be prepared and divided into training, validation, and test sets.

## Team Responsibilities

| Member | Responsibilities |
|---|---|
| **Ahmed** | GitHub management, EDA, preprocessing, data splitting, Model A, Week 4 status update |
| **Akua** | Model B, code integration, technical report |
| **Sai** | Model C, model evaluation and comparison, slides, video, final submission |

All three members will contribute to the report and presentation.

## Models

We will develop and compare three models:

| Model | Approach | Owner |
|---|---|---|
| Model A | CNN trained from scratch | Ahmed |
| Model B | MobileNetV2 Transfer Learning | Akua |
| Model C | EfficientNetB0 Transfer Learning | Sai |

All models will use the same training, validation, and test splits for a fair comparison.

## Evaluation

We will compare the models using:

- Accuracy
- Precision and Recall
- F1-score
- Confusion Matrix
- Training and Validation Curves
- Error Analysis

We will also review overfitting, model limitations, and possible improvements.

## Repository Structure

- **data/**: Dataset information, class labels, and data splits
- **notebooks/**: EDA, preprocessing, and model notebooks
- **results/**: Evaluation metrics, charts, and comparisons
- **report/**: Technical report and supporting figures

## Project Status

-  Project and dataset selection
-  Team responsibilities
-  GitHub repository setup
-  Data exploration (EDA)
-  Data preprocessing and splitting
-  Model A: CNN
-  Model B: MobileNetV2
-  Model C: EfficientNetB0
-  Model evaluation and comparison
-  Code integration and testing
-  Technical report
-  Slides and video presentation
-  Final submission

## Final Deliverables

1. Technical Report (PDF)
2. GitHub Repository with Code
3. Recorded Video Presentation (10–12 minutes)

**Final Deadline: December 7, 2026, at 11:59 PM**
