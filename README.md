# Real-time-Video-and-Audio-Streaming-Application
This project demonstrates a real-time video and audio streaming application that allows users to transmit and receive video and audio frames over a network. The server code captures video frames from a video file, resizes them, and sends them to connected clients using UDP. Simultaneously, it reads audio frames from a WAV file and streams them to clients using TCP.

The client code receives the transmitted video and audio frames, decodes and displays the video frames using OpenCV, and plays the audio frames using the PyAudio library. The system maintains synchronization between video and audio streams to ensure a smooth and synchronized playback experience.

Please feel free to modify the project name and description according to your preference or add any additional information that you find relevant. When creating an online repository, remember to include a README.md file with the project's details, setup instructions, and any dependencies required for running the application successfully.


OpenCV (cv2):

Used for video frame capture, resizing, and encoding/decoding.
Install using: pip install opencv-python


imutils:

Provides convenience functions for OpenCV, especially for resizing images.
Install using: pip install imutils


Numpy:

Used for numerical operations and processing of arrays, especially for handling image data.
Install using: pip install numpy


pyaudio:

Used for audio input/output, especially for real-time audio streaming.
Install using: pip install pyaudio
