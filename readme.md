\# Hand Gesture Meme Detector (MediaPipe + OpenCV)



This project is a fun \*\*computer vision application\*\* that uses MediaPipe and OpenCV to detect hand and face landmarks from a live webcam feed and trigger a meme reaction based on the position of the hand relative to the chin.



If the hand is placed \*\*below the chin\*\*, the program displays a meme image. Otherwise, a default base image is shown.



The project demonstrates how \*\*real-time landmark detection\*\* and \*\*gesture-based logic\*\* can be used to build interactive visual applications.



\---



\## Features



\* Real-time \*\*hand landmark detection\*\*

\* Real-time \*\*face mesh detection\*\*

\* Gesture-based interaction

\* Meme switching based on hand position

\* Live webcam visualization

\* Side-by-side display of webcam feed and meme reaction



\---



\## How It Works



1\. The webcam captures frames in real time.

2\. MediaPipe Hands detects hand landmarks.

3\. MediaPipe Face Mesh detects facial landmarks.

4\. The program identifies the \*\*chin position\*\* from the face mesh.

5\. The \*\*wrist position\*\* from the detected hand is compared to the chin.

6\. If the wrist is \*\*below the chin\*\*, a meme image is displayed.

7\. Otherwise, the default image is shown.



\---



\## Project Structure



hand-gesture-meme-detector/



main.py

base\_img.png

meme.png

requirements.txt

README.md



\---



\## Installation



Clone the repository:



git clone https://github.com/YOUR\_USERNAME/hand-gesture-meme-detector.git



cd hand-gesture-meme-detector



Install dependencies:



pip install -r requirements.txt



\---



\## Running the Project



Make sure the following image files are present in the project folder:



base\_img.png

meme.png



Then run the script:



python main.py



Your webcam will open and the system will detect your hand position in real time.



\---



\## Technologies Used



\* Python

\* OpenCV

\* MediaPipe

\* NumPy

\* Matplotlib



\---



\## Future Improvements



Possible extensions for this project:



\* Gesture recognition (thumbs up, peace sign, etc.)

\* Multiple meme reactions

\* Face expression detection

\* Real-time overlays instead of side-by-side images

\* Deploying the project as a web application



\---



\## Learning Outcomes



This project demonstrates:



\* Real-time computer vision pipelines

\* Landmark detection using MediaPipe

\* Gesture-based interaction design

\* Webcam video processing using OpenCV

\* Integrating face and hand detection models



\---





