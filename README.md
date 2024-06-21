# DeepFake-Detection
The project aims to detect deepfake videos using deep learning techniques like ResNext and LSTM. It uses a Res-Net Convolution Neural Network to extract frame level features which are then used to train a Long short Term Memory (LTSM) based Recurrent Neural Network (RNN) to clasify whether the video is an orginal or deepfake. 

## Preprocessing
  - Load the dataset
  - Split the video into frames
  - crop the face from each frame
  - save the face cropped video
    
## Model and training
  - It will load the preprocessed video and labels from a csv file.
  - Create a pytorch model using transfer learning with RestNext50 and LSTM.
  - Split the data into train and test data
  - Train the model
  - Test the model
  - save the model in .pt file
    
 ## Predicting
  - Load the saved pytorch model
  - Predict the output based in trained weights.
