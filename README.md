This project explores the use of computer vision technology to assist visually impaired individuals in navigating their environment safely and independently. Our system utilizes a combination of lane, object, and obstacle detection, providing real-time auditory navigation cues.

Key Features:
Lane Detection: Using OpenCV, we preprocess video frames to enhance edge detection and apply the Hough transform to identify lane markers.
Object and Obstacle Detection: We implement the YOLO (You Only Look Once) algorithm, renowned for its accuracy and real-time performance, to classify and localize objects around the user.
Auditory Feedback: The system provides navigation instructions via a user-friendly auditory interface, ensuring effective communication without overwhelming the user.
Testing and Results:
Robustness and Reliability: Extensive testing was conducted in diverse environments, including urban areas and indoor spaces. Preliminary results show that the model accurately detects lanes and objects, delivering actionable navigation instructions.
Future Enhancements: Planned improvements include better performance in low-light conditions, an expanded range of detectable objects, and optimized auditory feedback to make the system more intuitive.
This project aims to enhance the independence and safety of visually impaired individuals by integrating these computer vision models into a seamless navigation application.
