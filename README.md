# Machine Learning Experiments

A collection of hands-on learning projects covering classical machine learning, computer vision, and natural language processing. Each notebook documents the objective, implementation, and findings of the experiment.

The results below are taken from the evaluation outputs saved in the notebooks. Where multiple models were compared, the table highlights the best recorded model.

## Classical Machine Learning

| Project | Model | Result |
| --- | --- | --- |
| [Wine Quality Prediction](classical-ml/wine-quality-prediction/Wine%20Quality%20Prediction.ipynb) | Random Forest Regressor | Test R²: **0.529**; MAE: **0.392** |
| [Spotify Song Classification](classical-ml/spotify-song-classification/Spotify%20Song%20Classification.ipynb) | XGBoost Classifier | Test accuracy: **77.2%** |
| [Student Grade Prediction](classical-ml/student-grade-prediction/Student%27s%20Final%20Grade%20Prediction.ipynb) | ExtraTrees Regressor | Test R²: **0.865** |
| [Admission Prediction](classical-ml/admission-prediction/Admission%20Prediction.ipynb) | Linear Regression | Test R²: **0.763**; MAE: **0.0469** |
| [Forest Fire Prediction](classical-ml/forest-fire-prediction/Forest%20Fires%20Prediction.ipynb) | Support Vector Regressor (SVR) | Test MAE: **0.771**; RMSE: **1.735** |
| [Father-Son Height Prediction](classical-ml/father-son-height-prediction/Son%27s%20Height%20Prediction.ipynb) | Linear Regression | Exploratory height relationship analysis |

## Computer Vision

| Project | Model | Result and Demo |
| --- | --- | --- |
| [Teachable Machine Image Classification](computer-vision/teachable-machine-pothole/teachable-machine-pothole.ipynb) | Teachable Machine (TensorFlow/Keras) | [Video demonstration](https://drive.google.com/file/d/1KApAVyWKFQjdJK9LqyFgRfgbOLpYrXrk/view?usp=sharing) |
| [YOLO Food Detection](computer-vision/yolo-food-detection/yolo-food-detection.ipynb) | YOLOv8n | Validation mAP@0.5: **0.968**; mAP@0.5:0.95: **0.774** (65 images) · [Video demonstration](https://drive.google.com/file/d/1rWk93D-Gllb9aKEO_FIuAmHt1v9n4H1u/view?usp=sharing) |
| [YOLO and TrOCR](computer-vision/yolo-trocr-ocr/yolo-trocr-ocr.ipynb) | YOLO (detection) + TrOCR Small (recognition) | TrOCR evaluation CER: **6.21%** · [Video demonstration](https://drive.google.com/file/d/1a0P0vyt7ynMgn9RJg09_QYXfQOb3BJCT/view?usp=sharing) |
| [Vehicle Tracking](computer-vision/vehicle-tracking/vehicle-tracking.ipynb) | YOLOv8s with object tracking | Highway vehicle tracking and unique-ID counting |

## Natural Language Processing

| Project | Model or Method | Result |
| --- | --- | --- |
| [Python Word-Sense Classification](nlp/python-word-sense-classification/Python%20Classifier.ipynb) | TF-IDF + Multinomial Naive Bayes | Training accuracy: **89.7%** |
| [Semantic FAQ Search](nlp/semantic-faq-search/semantic-faq-search.ipynb) | Sentence Transformer (`all-MiniLM-L6-v2`) + cosine similarity | [240 synthetic FAQ entries](nlp/semantic-faq-search/faq.csv) across 12 categories; [36 labeled evaluation queries](nlp/semantic-faq-search/evaluation_queries.csv) for Top-1 accuracy, Recall@3, and MRR |

## Datasets

The experiments use a variety of datasets, including tabular, image, video, and text data. Some datasets are included in the repository, while others are obtained from external sources referenced in the notebooks.
