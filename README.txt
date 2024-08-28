## Do Hyeon Cha, KAIST
## Yuji Ko, Pusan Nat'l Univ School of Dentistry

Scripts, models, data for the upcoming competition

1. "raw" folder consists of a CNN-FCL regression model with raw augmented-images for training

 
2. "mask" folder consists of U-Net segmentation network and finally-selected transfer learning model (InceptionResNetV2 with fine-tuned hyperparameters)
 
- Final models are saved in pediatric_dental_age_prediction/mask/model

- Final evalutation metrics are saved in pediatric_dental_age_prediction/mask/eval
