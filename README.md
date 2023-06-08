# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.</br></br>

<h3 >The working of the project</h3>

<ul><li>As you can see the<b> above screenshot</b> where the landmarks are detected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>

<center>
  <img src="https://github.com/aloksinghrcr65/Driver_Drowsiness_Detection/assets/130700098/fdcca10e-7f87-474b-a05f-1fc88a8b4fc0" align="left" height="350">
  <img src="https://github.com/aloksinghrcr65/Driver_Drowsiness_Detection/assets/130700098/a5f0e283-31f2-42d7-9521-40af84717bd7" align="right" height="350">
</center></br>



<!-- <center>
  <img src="https://github.com/aloksinghrcr65/Driver_Drowsiness_Detection/assets/130700098/a5f0e283-31f2-42d7-9521-40af84717bd7" align="top" height="350">
</center></br> -->
<!-- <img src="https://raw.githubusercontent.com/infoaryan/Driver-Drowsiness-Detection/master/screenshots/drowsy.jpg" align="center" height="350">
<img src="https://raw.githubusercontent.com/infoaryan/Driver-Drowsiness-Detection/master/screenshots/sleepy.jpg" align="center" height="350">
 -->
