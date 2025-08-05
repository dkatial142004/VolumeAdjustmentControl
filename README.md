# VolumeAdjustmentControl
A vision-based real-time hand gesture system enables personalized, touchless volume control.

OVERVIEW : 
This project presents an intelligent vision-based real-time hand gesture recognition system that enables users to control volume levels using natural hand gestures — eliminating the need for physical interaction. The system uses computer vision and deep learning techniques to recognize specific hand movements and adjusts volume dynamically in response. It is designed to be personalized, intuitive, and touchless, ensuring a hygienic and futuristic user experience.

![Gesture Control Demo](image.png)
ABOVE : Demonstration of real-time volume adjustment using the distance between the thumb and index finger.

OBJECIVE :
The aim of this project is to provide a **touchless, intuitive, and interactive user interface** that improves human-computer interaction by replacing traditional volume control mechanisms with hand gestures.


HOW IT WORKS:

1. **Capture Frame** – The webcam continuously captures live frames.
2. **Detect Hand** – MediaPipe identifies the presence of hands and returns 21 landmarks.
3. **Track Distance** – The distance between the **thumb tip** and **index finger tip** is calculated.
4. **Map to Volume** – This distance is linearly mapped to the system’s volume range using PyCaw.
5. **Visual Feedback** – The system shows a volume bar and real-time percentage on the screen.

   
FEATURES :
-  Real-time hand detection and gesture tracking  
-  Distance-based gesture mapping to control system volume  
-  Touchless interaction enhances accessibility  
-  Personalized tuning for different hand sizes and movement ranges  
-  Smooth and responsive control via system API
