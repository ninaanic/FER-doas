Content of zip archive for project License plate number recognition:
--> folders
        images                                  - a folder containing 103 images of vehicles used to evaluate the model
        test                                    - a folder containing 5 images of the vehicle used for display

--> txt file 
        labels.txt                              -  a txt file containing the actual registrations of all cars from the data set required to evaluate the model 

--> jupyter notebooks
        processing.ipynb                        - a jupyter notebook containing python code for image processing and detection of characters from license plates 
        evaluation.ipynb                        - a jupyter notebook containing python code for testing our models and functions on larger set of data 

--> JPEG image
        image1.jpg                              - an image of the vehicle processed in processing.ipynb jupyter notebook

--> pre-trained model architectures and weights
        wpod-net.h5                             - a hierarchical data format containing weights of pre-trained model for detection and extraction license plates of vehicle images
        wpod-net.json                           - a json file containing architecture of pre-trained model for detection and extraction license plates of vehicle images
        local_utils.py                          - a python script containing some functions used for processing data from Wpod-Net
        License_character_recognition_weight.h5 - a hierarchical data format containing weights of pre-trained model for letter and number recognition from image
        MobileNets_character_recognition.json   - a json file containing architecture of pre-trained model for letter and number recognition from image
        license_character_classes.npy           - a binary file containing origin label classes of pre-trained model for letter and number recognition from image