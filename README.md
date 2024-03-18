# face_recognition
Face recognition app based on Siamese neural network and metric learning.
Implementation of "Siamese Neural Networks for One-shot Image Recognition" paper on self-collected data, being my images and creating ((anchor, negative),0) and ((anchor, positive),1) data points and classifying as same or different based on the final fully connected distance layer. Before reaching the distance layer we have the Siamese network. 

-- Due to certain issues with the directory in VS Code, could not be uploaded to Github.

Structure:

  -- Data Preprocessing

  -- Dataset creation

  --Model Embedding creation

  --Distance layer and classification layer

  --Combination training for certain EPOCHs

  -- Prediction of real-time data

  --FastAPI endpoint, which takes an image and outputs the result of authentication of the user (in this case me)
