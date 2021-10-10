## Sign language detection using sequences

#### Description
Sign langauge detection has been a topic that has been researched for a long time, but still there are many issues to be addressed, one such important issue being that sign language majorly consists of action instead of signs,this means there will be a problem of errors and/or redundancy in a sign language to voice/text conversion system, this project addresses this issues by using sequences of multiple frames for each action to train and predict instead of single frame images.

#### The tools and skills required for this project include:
- Python
- TensorFlow
- keras
- sklearn
- Deep learning(LSTM model)
- mediapipe holistic
- opencv

A code block of this project, runs the program to collect the vidual data from the user itself, once the block starts running, 30 instances of 30 frames are collected for 15 different signs, the user has to make sure to do the appropriate signs during this time.
Once the data is collected, folders will be created in the specified path(Make sure to change the path according to your situation) and data will be stored in various files in the folders.

The data that i have collected myself is in too many distinct files to be uploaded on github

The final block of the code runs the final apllication, this only works once the data is collected and the model is trained.
action files are the weights that i have obtained for the models i have trained use them if you wish.
