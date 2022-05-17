# Breast-Cancer-Segmentation-Final-Project

Code Contribution

Model_And_Testing_Base.ipynb : Alex Thiesmeyer

- This file is currently set up to fine-tune and test a pretrained DeepLabV3 model with weighted cross-entropy loss in Google Colab. The data can be found at https://drive.google.com/drive/folders/1zqbdkQF8i5cEmZOGmbdQm-EP8dRYtvss and must be loaded onto the user's local drive.


DataAugmentation.ipynb : Alex Benanti 

- This file augments the training data used in the model and testing to create new data that can be used for further model training via the CutBlur and Cutout algorithms. The file should operate properly by simply running the commands given that the data is properly installed into the notebook you are running on (same as with the model and testing).


Transfer_Learning.ipynb: Ronan Manvelian

- This file slightly refactors the code Alex T. wrote and performs five different transfer learning methodologies that involve the freezing and fine-tuning of entire layers, as well as specific layer parameters, of our DeepLabV3 model. The transfer learning results should be easily obtainable by simply running the commands in the notebook cells.
