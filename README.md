# ASRS
The project requires tensorflow object detection API to detect the specie of the bird. You have to setup the whole file system structure first to run the project.

The model is trained on the Google colab. And the script use to train the model is in "Create Model" folder.
Model runs on AWS EC2 instance and uses Apache web hosting to host the web UI. 
All the web UI files are in "Web UI" folder.

"front.html" is used to take the input.
"save_file.py" is a cgi file used to save the photo on AWS EC2 instance and also to start the model on it.
"disp.py" is used to display the specie of bird and the information.



kj
