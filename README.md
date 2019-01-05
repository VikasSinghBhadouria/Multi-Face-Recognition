# Multi-Face-Recognition
OpenCV based multi face recognition model.(Python based )
Capture multiple Faces from multiple users to be stored on a DataBase (dataset directory) 
and their details (id,names) to be stored in a separate CSV file .
A separate file for storing LBPH computed model.

Libraries needed : 
1.OpenCV
2.PIL(For image Processing)
3.Pandas
4. Os 

Create 2 directories :dataset ,trainer

Each separate Files for each independent function.
1.face_dataset.py= To create and update  dataset by clcicking images from the camera(upto 30 ) and storing in dataset folder.
2.face.training.py= To create and update the trainer.yml using LBPH model on the dataset.
3.face_recognition.py= TO start the cam and recognize the faces on live video .


Based on original code by Anirban Kar: https://github.com/thecodacus/Face-Recognition    

