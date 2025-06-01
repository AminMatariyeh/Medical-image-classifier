This project uses a Convolutional Neural Network (CNN) 
to classify chest X-ray images as either Normal 
or Pneumonia. It was trained using publicly available data 
from Kaggle and allows you to:

1. Train the model with 1300 pneumonia and normal chest xrays
(ML_normal_vs_pneumonia.py) 
2. Use the trained model for predicting images 
(ML_normal_vs_pneumonia.h5) 
3. Test it with labeled samples (predict_image.py)
4. Load and classify any image from your
computer (select_file.py)

Currently, the model does at times produce false 
positives; however it rarely does produce false 
negatives for practicality as a false negative is
significantly worse than a false positive.

To use, either run the predict_image.py to test from the test dataset, or use the select_file.py to select external images (I provided a few I found online Normal_tester, Normal_tester1, Pneumonia_tester, Pneumonia_tester1) 


Model trained on the Chest X-Ray Images (Pneumonia) 
dataset from Kaggle.
