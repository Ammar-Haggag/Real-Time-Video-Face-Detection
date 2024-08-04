# Real-Time-Video-Face-Detection

![Face Detection_screenshot_04 08 2024](https://github.com/user-attachments/assets/7336a2a6-fc8a-4820-861d-67928562aec7)


## Real-Time Face Detection with C++ and Raspberry Pi

### Overview

This project implements real-time face detection using a laptop camera with C++ on a Raspberry Pi 2. Leveraging the OpenCV library, the application is capable of detecting faces in video streams, providing a foundation for further development into facial recognition and other advanced features.

### Features

- **Real-Time Video Processing:** Utilizes a laptop camera to capture and process video frames in real time.
- **Face Detection:** Implements Haar Cascades for efficient and accurate face detection.
- **Optimized Performance:** Fine-tuned for smooth processing on the Raspberry Pi's limited hardware resources.

### Getting Started

#### Prerequisites

- Raspberry Pi 2
- Laptop with a camera
- C++ compiler (e.g., g++)
- OpenCV library

#### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/real-time-face-detection.git
    cd real-time-face-detection
    ```

2. **Install Dependencies:**
    Follow the instructions to install OpenCV on your system. [OpenCV Installation Guide](https://docs.opencv.org/master/df/d65/tutorial_table_of_content_introduction.html)

3. **Compile the Code:**
    ```bash
    g++ -o face_detection main.cpp `pkg-config --cflags --libs opencv4`
    ```

4. **Run the Application:**
    ```bash
    ./face_detection
    ```

### Usage

Once the application is running, it will capture video from your laptop camera and detect faces in real time. The detected faces will be highlighted with bounding boxes.

### Future Plans

- **Facial Recognition:** Implement deep learning models for facial recognition.
- **User Interface:** Develop a user-friendly GUI for easier interaction.
- **Edge Computing:** Explore applications in security systems and smart home devices.

### Learning Outcomes

- Enhanced skills in C++ programming and image processing.
- Hands-on experience with Raspberry Pi hardware.
- Deeper understanding of machine learning algorithms and their applications.

### Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.


