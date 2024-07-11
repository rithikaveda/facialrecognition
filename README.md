**Real-Time Face Recognition using OpenCV and face_recognition**<br>
**Project Overview**<br><br>
This project demonstrates a real-time face recognition system using OpenCV and the face_recognition library. It captures video from a webcam, detects faces in the video feed, and recognizes known individuals by comparing detected faces with pre-loaded images.<br><br>
**Brief Explanation**<br>
**Load and Encode Known Faces**: <br>
The script loads images of known individuals (kcr.jpg, obama.jpg, and trump.jpg) and generates their face encodings using the face_recognition library.<br>
**Initialize Webcam**: <br>
It initializes the webcam for video capture using OpenCV (cv2.VideoCapture(0)).<br>
**Detect and Recognize Faces**:<br>
In a loop, the script captures frames from the webcam, detects faces in each frame, and computes their face encodings.<br>
**Match Faces**: <br>
For each detected face, it compares the encoding with known face encodings to find matches. If a match is found, it assigns the corresponding name to the face.<br>
**Display Results**:<br>
The script draws rectangles around detected faces and displays the name of the recognized individual on the video feed. The loop continues until the 'q' key is pressed, at which point the webcam is released and the window is closed.<br><br>




**Usage Instructions**<br>
Run the face recognition script:<br>

bash<br>
python face_recognition_script.py<br>
