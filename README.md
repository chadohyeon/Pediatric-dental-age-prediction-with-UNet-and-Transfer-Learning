## Developed by Do Hyeon Cha, MD, MS (Yonsei University College of Medicine, KAIST)
## Pusan Nat'l Univ School of Dentistry (Yuji Ko, DDS): Idea pitching, data curation, dental age auxiliary confirmation.

<img width="1274" height="837" alt="teethAge" src="https://github.com/user-attachments/assets/3c0c1956-0e17-453c-8884-3c8123d680a7" />


Scripts, models, data for the medical AI competition

1. "raw" folder consists of a CNN-FCL regression model with raw augmented-images for training

 
2. "mask" folder consists of U-Net segmentation network and finally-selected transfer learning model (InceptionResNetV2 with fine-tuned hyperparameters)
 
- Final models are saved in pediatric_dental_age_prediction/mask/model

- Final evalutation metrics are saved in pediatric_dental_age_prediction/mask/eval
