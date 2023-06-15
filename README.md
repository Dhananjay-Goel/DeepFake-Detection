# DeepFake-Detection

# Model Creation
  - You will be able to preprocess the dataset, train a pytorch model of your own, predict on new unseen data using your model.
## Preprocessing
  - Load the dataset
  - Split the video into frames
  - crop the face from each frame
  - save the face cropped video
## Model and train
  - It will load the preprocessed video and labels from a csv file.
  - Create a pytorch model using transfer learning with RestNext50 and LSTM.
  - Split the data into train and test data
  - Train the model
  - Test the model
  - save the model in .pt file
 ## Predict 
  - Load the saved pytorch model
  - Predict the output based in trained weights.
