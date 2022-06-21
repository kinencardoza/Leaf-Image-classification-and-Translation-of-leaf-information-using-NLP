# Leaf-Image-classification-and-Translation-of-leaf-information-using-NLP
This is an android app that would classify a leaf using image classification algorithms (transfer learning and CNN) and give the user results and important information in their language of choice using NLP (built from scratch and IndicTrans models) for the translation.

#1 Running The app
  
  *download this repositorie's folder, open and run using android studio code.

#2 Running the NLP server on desktop
  https://github.com/kinencardoza/NLP-server-leaf-classification-app-

  *install miniconda and download the folder at the link above and place it somewhere at your desktop. Go to the dir "FlaskApp" and run the command "python main.py". Take the url and put it into the Thirdactivity.java at line 96 in the sendRequest() every time you start the server.

#3 Running the IndicTrans server on collab
  https://colab.research.google.com/drive/1LnY2Fq2nih_0fCvYlGj7J3OIMmLfQYcR?usp=sharing
  
  *run all cells and copy the ngrok tunnel url and place it into the Thirdactivity.java at line 96 in the sendRequest() every time you start the server.
