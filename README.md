# -Automated-Student-Attendance-System-By-Real-Time-Face-Recognition-
This project Automatically mark Attendance of student based on Real Time Face Recognition using python libraries.<br /> 
<br />
 <br />
 
<h2>Project Objctives:</h2>
<ol>
  <li>Detection</li>
  <li>Recognition</li>
  <li>Updating record in Excel</li>
  <li>GUI for Attendence Marking</li>
 </ol>
 <br />
 <br />
 <h2>Detection</h2>
 Detection is done by the help of OpenCV and Haar cascades
<br />
 <br />
 
Face detection using Haar cascades is a machine learning based approach where a cascade function is trained with a set of input data. OpenCV already contains many pre-trained classifiers for face, eyes, smiles, etc.. Today we will be using the face classifier. You can experiment with other classifiers as well.
 <br />
 <br />
 
<h2>Recognition</h2>
 Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
<br />
 <br />
 
LBPH is one of the easiest face recognition algorithms. It can represent local features in the images. It is possible to get great results (mainly in a controlled environment). It is robust against monotonic gray scale transformations. It is provided by the OpenCV library (Open Source Computer Vision Library).
  <br />
 <br />
 
 <h2>Updating record in Excel</h2>
After the face recognition the code will automatically create an entry of the the student into the excel file .
<br />
<br />
<h2> Library Used</h2>
<ul>
 <li>OpenCV-contrib-python</li>
<li>Pandas</li>
<li>Numpy</li>
<li>csv</li>
<li>Pilow</li>


<li>cv2</li>
<li>time</li>
<li>pyttsx3</li>
<li>datetime</li>
<li>openpyxl</li>
<li>tkinter</li>
<li>requests</li>
 <li>os/li>
<li>shutil</li>

 
</ul>
<br />
<br />
<h2>Instructions</h2>
<ul>
<li>Download or clone my Repository to your device</li>
 <li>Go through the notes.txt and download all the necessary files and import all the libraries</li?
 <li>Create a TrainingImage folder in a project folder.</li>
<li>Open attendance.ipynb and automaticAttendance.ipynb, change all the path accoriding to your system</li>
 <li>Run attandance.py file</li>
  <li>After you run the project you have to register your face so that system can identify you, so click on register new student</li>
  <li>A small window will pop up in that you have to enter you ID and name and then click on Take Image button</li>
  <li>After clicking Take Image button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named TrainingImage. more you give the image to system, the better it will perform while recognising the face.</li>
  <li>Then you have to click on Train Image button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.</li>
  <li>After training model click on Automatic Attendance ,you have to enter the subject name and then it can fill attendace by your face using our trained model.</li>
 <li>Create a .csv file with name of the file as the subject name</li>
 <li>Therefore the entries will be made as soon as face is recognised</li>
 <li>You can view the attendance after clicking View Attendance button. It will show record in tabular format</li>
</ul>
<br  />
<br  />
<h2>Project Snapshot</h2>

    ![alt text]("C:\Users\jignesh\Desktop\6th sem\internship project\Untitled.png")
