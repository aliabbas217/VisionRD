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

 The DLA60 pre-trained model is used with modifications done as the backbone for classification. The architecture built manually includes:
   - **Neck:** Added layers for further feature processing.
   - **Heads:** Different heads are created for specific tasks such as predicting actions, bounding boxes, keypoints, and modes.
     

### Approach
 We *merged* the action and annotation data in a json file using the **utils/xml2coco.py** and *extracted* the annotations' individual categories i.e the bounding boxes,keypoints,modes 
 by *coding* CustomImageDataset.py. The data is then *transformed* and with *measuring losses* and *optimization* by adam in **loop.py** .And the *necks and heads* are built with using 
 and *modifying* the dla provided **arch/backbone/dla.py** backbone architecture.

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
      import pandas as pd
      

### Interactive Demo
 Try the live version of the model here: 
[Live Demo](https://example.com)

### Contact
   - [Ali Abbas Baig](mailto:)
   - [Syeda Aiman Mumtaz Sherazi](mailto:aimanmumtaz27@gmail.com)
   - [Muhammad anas](mailto:)
  
### Tensorboard screenshots 


