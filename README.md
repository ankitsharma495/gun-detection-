# Gun Detection using Python and OpenCV

This project implements a real-time gun detection system using Python and OpenCV. The system processes video feeds to identify firearms, leveraging Haar cascades for object detection. Designed for enhanced security and surveillance, this project demonstrates efficient and accurate threat detection.

## Features
- Real-time firearm detection with high accuracy.
- Processes live video streams efficiently.
- Highlights detected firearms using bounding boxes in the video feed.
- Easy-to-integrate solution for security and surveillance systems.

## Tech Stack
- **Programming Language**: Python
- **Libraries and Tools**:
  - OpenCV: For video processing and object detection.
  - NumPy: For numerical computations.
  - Matplotlib: For result visualization (if applicable).
- **Machine Learning**: Haar cascades for object detection.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ankitsharma495/gun-detection.git
   cd gun-detection
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python gun_detection.py
   ```

## How It Works
1. The system uses Haar cascades pre-trained on firearm datasets to detect guns in video frames.
2. Processes each frame of the video feed in real-time.
3. Highlights identified firearms with bounding boxes for visual indication.

## Applications
- Security monitoring in public areas.
- Automated surveillance for restricted zones.
- Threat detection in sensitive environments.

## Future Enhancements
- Replace Haar cascades with deep learning models like YOLO or SSD for improved accuracy.
- Add multi-camera support for large-scale surveillance systems.
- Enhance performance for low-latency environments.

## Contributing
Contributions are welcome! Please feel free to fork the repository, create issues, or submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

---

For more details, visit the [repository](https://github.com/ankitsharma495/gun-detection).
