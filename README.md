# Face-Recognition-Attendance-Tracker
The model is designed to capture images through a webcam, train them using OpenCV and Face Recognition libraries, and automatically record the attendance in an excel sheet.

### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)
- Pycharm IDE 


### Project Structure
- First we have to create a folder named `TrainingImage` in our project folder.  
- We need to run `AMS_Run.py`.After running we need to give our face data to the system to enter our enrollment ID and name in the box and then click on the `Take Images` button.
- It will collect 71 images of our faces, and it save images in the `TrainingImage` folder
- After that, we need to train our model(to train a model click on the `Train Image` button).
- It will take 30-40 seconds for training.
- After training click on `Automatic Attendance`, it can fill attendance by our face using our trained model (the model will save in `TrainingImageLabel` )
- It will create a `.csv` file of attendance according to time & subject.
- We can store data in the database (install Pycharm IDE)
- `Manually Fill Attendance` Button in UI is for filling a manual attendance (without face recognition), it also create a `.csv` and store it in a database.
