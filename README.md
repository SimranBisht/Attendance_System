The main idea of the project is to demonstrate Face Detection using OpenCV and Python.

OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library which provides image and video processing. It has algorithms that can be used to detect and identify faces, objects, track moving objects in a video or in an image, follow eye movements etc.

I have used Haar Cascade classifier(haarcascade_frontalface_default.xml) which is used to detect the object for which it has been trained for. It is an XML file that has classifier for face,eyes etc.

Files :-<br />
1.Attendance - It stores attendance in the form of a CSV file, each time a new attendance is recorded.<br />
2.ImagesUnknown - It contains images which the classifer is unable to identify.<br />
3.StudentDetails - It contains a CSV file that stores ID and Names of the students whose images have been trained on by the model.<br />
4.TrainingImage - It contains images of the user which have recorded their attendance. There are 61 images per user on which the model is trained.<br />
5.attendance - This is a Python file which contains the code for all the tasks performed.<br />

Process - A user has to first enter his/her name along with his roll number or any ID. If any of the details are wrongly entered then prompt messages are given. After that the user has to click on the 'Capture Image' button. Camera window pops up and images are taken. User now has to click on the 'Train Model' button for the model to train. For convenience, STEP 1 and STEP 2 labels have been provided. User can now hit the 'Mark Attendance' button to mark attendance. At the bottom of the screen status is displayed after each operation is performed.

Programming language used is Python.

