## Solely developed by Do Hyeon Cha, MD, MS (Yonsei University College of Medicine, KAIST)
## Pusan Nat'l Univ School of Dentistry: Idea pitching, data curation, dental age auxiliary confirmation.

Scripts, models, data for the medical AI competition

1. "raw" folder consists of a CNN-FCL regression model with raw augmented-images for training

 
2. "mask" folder consists of U-Net segmentation network and finally-selected transfer learning model (InceptionResNetV2 with fine-tuned hyperparameters)
 
- Final models are saved in pediatric_dental_age_prediction/mask/model

- Final evalutation metrics are saved in pediatric_dental_age_prediction/mask/eval
