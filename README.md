# VisionRD
This repository is for VisionRD Hackathon

## Table of Content
1. [Problem Statement](#ProblemStatement)
2. [Solution Description](#SolutionDescription)
3. [Approach](#Approach)
4. [Data Preprocessing](#DataPreprocessing)
5. [Features](#Features)
6. [Technologies Used](#TechnologiesUsed)
7. [Installation and Running](#installationandrunning)
8. [Usage](#Usage)
9. [Demo](#InteractiveDemo)
10. [Contact](#Contact)
   
   

### Problem Statement
   The task involves predicting actions, bounding boxes, and keypoints in the GTEA dataset using supervised learning.


### Solution Description
   The DLA60 pre-trained model is used as the backbone for classification. The architecture also includes:
   - **Neck:** Added layers for further feature processing.
   - **Heads:** Different heads are created for specific tasks such as predicting actions, bounding boxes, keypoints, and modes.
     
   The action and annotation data are merged using a custom script (xml_to_coco.py) and extracted into individual categories by CustomImageDataset.py. The data undergoes transformation      using dataloader/dataloader.py.


### Approach
   We used a linear regression model to predict the house prices based on the selected features. The dataset was preprocessed to handle missing values, and a simple train-test split was     applied for evaluation. We focused on the relationship between key features like area, bedrooms, and bathrooms to predict the target variable—house price.

### Data Preprocessing
   Here are the techniques used for the data preprocessing

### Features
- Regression model
- Real-time price predictions on housing related features.

### Technologies Used

- **Python**
- **pytorch**
- **Pandas**
- **Matpltlib**
- **TensorBoard**

### Installation and running
1. Install dependencies:
   pip install -r requirements.txt
2. Run the arch/model.py 
   

### Usage
   How to run the project once it’s set up. This could include training the model, making predictions, and interacting with any interface
1. **Training the Model:**
      To train the model, run:
       python
      python train.py 
2. **Making Predictions**: After training, use the following code to make predictions on new medical images:
      ```import pandas as pd
      

### Interactive Demo
   Try the live version of the house price prediction model here: 
[Live Demo](https://example.com)

### Contact
   - [Ali Abbas Baig](mailto:)
   - [Syeda Aiman Mumtaz Sherazi](mailto:aimanmumtaz27@gmail.com)
   - [Muhammad anas](mailto:)
  
### Tensorboard screenshots 


