# Efficient face recognition system
 A fast and accurate face recognition systen that requires very less data to train on. 
 The faces in the input images are first converted into a set of 128 features using Open Face, as it is always easier to train on tabular data compared to images.
 This data is then trained on a simple ANN to obtain a tes accuracy of about 96%. 
 
 ## Using the code
 The current code is trained on 5 famous people (/train folder). The dataset contains around 30 images of each person. 
 It can identify between these 5 people and additionally, if a test input of a person not among these 5 people is provided, it gives the output as "random"
 


