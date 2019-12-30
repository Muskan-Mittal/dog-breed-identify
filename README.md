# dog-breed-identify

This notebook contains a solution to the dog breed identification competition held on Kaggle. The dataset can be downloaded from Kaggle. The dataset contains around 10000 images of 120 different species of dogs. The model could predict the species of dogs with a loss of 0.4959 on the Kaggle submission test set. 
<br>
I used the pretrained Inception V3 Model by Google as a feature extractor and removed the final output layer. I added some additional layers after the extractor before the final classification layer. Good results could be obtained by leveaging the pretrained weights of Inception Model.