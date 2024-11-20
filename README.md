Assistive Object Detection and Navigation System for the Visually Impaired:



This project is an advanced computer vision-based assistive system designed to aid visually impaired individuals in identifying objects and navigating their surroundings. Leveraging YOLOv8 for object detection, the system provides real-time feedback on:

Distance Estimation: Measures the distance between the user and a selected target object, ensuring spatial awareness.
Directional Guidance: Determines the direction the user should move to reach the target object and provides turn-by-turn navigation instructions.
Voice Interaction: Uses speech recognition to allow users to select objects of interest and provides real-time voice feedback for distance and direction.
----------------Key Features
Object Selection via Voice Commands: Users can specify the object they wish to locate using natural speech.
Real-Time Object Detection and Tracking: YOLOv8 is utilized for robust object detection and tracking across video frames.
Distance and Direction Monitoring: Calculates the distance and direction (left, right, straight) between the user and the target object.
Interactive Voice Feedback: Provides clear audio guidance on distance and direction, enabling intuitive navigation.
Save Functionality: Allows saving specific video frames for review or debugging.
Cross-Platform Compatibility: Built with Python, ensuring portability and ease of integration.
----------------------How It Works
Object Detection: Detects multiple objects in a video stream using YOLOv8.
Distance Estimation: Calculates the real-world distance to the target object based on its size and the camera's focal length.
Directional Guidance: Determines relative positioning and provides feedback on whether the user needs to turn left, right, or move straight to approach the target object.
Voice Interaction: Guides the user in selecting objects and navigating efficiently using text-to-speech (TTS) and speech recognition.
-----------------Use Case
This system is specifically designed for assisting visually impaired individuals in real-world environments, such as identifying personal belongings (e.g., cell phone, laptop) or navigating towards furniture (e.g., chairs, bed).

-----------Tech Stack
Programming Language: Python
Libraries:
ultralytics (YOLOv8) for object detection
cv2 (OpenCV) for image processing and tracking
speech_recognition for speech-to-text
pyttsx3 for text-to-speech
threading for real-time, synchronized voice feedback
