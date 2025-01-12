<h1>Hand Gesture Volume Control 🎛️🤚 </h1>
A computer vision-based system that allows users to control their system volume using simple hand gestures. This project leverages cutting-edge libraries like MediaPipe and OpenCV to track hand movements in real-time and translate them into volume adjustments.

<h2>Features 🚀 </h2>
<ul><li>Intuitive Gesture Control: Adjust system volume by moving your thumb and index finger closer or farther apart.</li>
<li>Real-Time Processing: Uses your webcam to track hand gestures and process them instantly.</li>
<li>Seamless Volume Adjustment: Automates volume control with precise tracking of hand landmarks.</li> </ul>

<h2>Technologies Used 🛠️</h2>
<ul><li>Python: The primary programming language for building the system.</li>
<li>OpenCV: For real-time video capture and processing. </li>
<li>MediaPipe: For accurate hand landmark detection and tracking. </li>
<li>PyAutoGUI: To interface with the system for volume adjustment.</li></ul>

<h2>How It Works 🖥️</h2>
<ol> <li>The webcam captures a real-time video feed of the user’s hand gestures. </li>
<li>MediaPipe detects and tracks the landmarks of the user’s hand (thumb and index finger).</li>
<li>OpenCV processes the video and calculates the distance between the thumb and index finger.</li>
<li>PyAutoGUI adjusts the system’s volume based on the detected distance.</li> </ol>
