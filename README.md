# Automated-Mouse
Virtual Mouse System Using Hand Gesture Recognition
#Overview:
This project introduces an automated virtual mouse system that utilizes real-time hand gesture recognition to control a computer cursor, providing a touchless alternative to traditional mouse input. It is particularly useful for users with mobility impairments or in situations where touchless interaction is preferred.

##Technology Stack:
OpenCV: Image processing to capture and process webcam input frame-by-frame.
MediaPipe: Detects and tracks hand landmarks for gesture recognition.
PyAutoGUI: Controls the computer's cursor, simulating real-time movement and clicks.

##How It Works:
Hand Landmark Detection: The system tracks hand landmarks, focusing on the index finger and thumb tips.
Cursor Movement: The x and y coordinates of the index finger tip are mapped to the screen's dimensions.
Click Simulation: A click is simulated when the thumb and index finger tips come close together.
Real-Time Processing: Processes each frame and flips it horizontally to ensure natural interaction.
