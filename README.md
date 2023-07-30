# Real-time Video and Audio Streaming Application

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

This project demonstrates a real-time video and audio streaming application that allows users to transmit and receive video and audio frames over a network. The server code captures video frames from a video file, resizes them, and sends them to connected clients using UDP. Simultaneously, it reads audio frames from a WAV file and streams them to clients using TCP.

The client code receives the transmitted video and audio frames, decodes and displays the video frames using OpenCV, and plays the audio frames using the PyAudio library. The system maintains synchronization between video and audio streams to ensure a smooth and synchronized playback experience.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required modules.

```bash
pip install opencv-python imutils numpy pyaudio
```

## Usage

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/Real-time-Video-and-Audio-Streaming-Application.git
   ```

2. Navigate to the project folder and run the server and client code on separate machines connected to the same network.

3. Make sure to have a video file (e.g., "yellow.mp4") in the project directory for the server to read frames from.

4. Run the server code on the machine you want to use as the server:
   ```
   python server.py
   ```

5. Run the client code on the machine you want to use as the client:
   ```
   python client.py
   ```

6. The client will display the received video frames, and you will hear the audio playback.

**Note:** Ensure that both the server and client have proper network connectivity and firewall settings to allow communication.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have improvements in mind, feel free to open a pull request.

## Acknowledgments

- The app was inspired by the need for a simple real-time video and audio streaming solution.
- Special thanks to the OpenCV, PyAudio, and NumPy communities for providing valuable resources.

## Disclaimer

Please note that this application is designed for demonstration purposes and may not be optimized for real-world use. It is essential to adhere to applicable laws and regulations related to video and audio streaming.

---
Replace "your-username" in the repository URL with your actual GitHub username. Adjust the content as needed based on additional features, improvements, or acknowledgments you might want to add. Also, update the instructions or usage information if there are any specific setup requirements for the project.
