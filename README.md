# IBM-internship-project-Face-Recognition-System
IBM internship project Face-Recognition System
      # Face Recognition Attendance System

A Python-based face recognition system that marks attendance using webcam input. This project uses `opencv`, `face_recognition`, and `numpy` libraries for detecting and recognizing faces.

## Description

This project captures images from a webcam, processes them to recognize faces, and logs the recognized faces' attendance in a CSV file. It uses the `face_recognition` library to detect and encode faces and `opencv` for image processing.

## Features

- Real-time face recognition using a webcam
- Attendance marking with timestamp
- Easy to add new faces for recognition
- CSV logging for attendance records

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository**
    ```bash
    git clone https://github.com/your-username/face-recognition-attendance-system.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd face-recognition-attendance-system
    ```

3. **Create a virtual environment (optional but recommended)**
    ```bash
    python -m venv myenv
    myenv\Scripts\activate  # On Windows
    source myenv/bin/activate  # On macOS/Linux
    ```

4. **Install the required packages**
    ```bash
    pip install -r requirements.txt
    ```

    Ensure you have the following packages:
    - `opencv-python`
    - `numpy`
    - `face_recognition`

5. **Install CMake (required for dlib)**
    ```bash
    choco install cmake  # On Windows using Chocolatey
    brew install cmake  # On macOS using Homebrew
    sudo apt-get install cmake  # On Linux using APT
    ```

## Usage

1. **Add images to the `ImagesAttendance` folder**  
   Place the images of people you want to recognize in the `ImagesAttendance` folder. The file names (without extension) will be used as the names for attendance.

2. **Run the script**
    ```bash
    python attendanceProject.py
    ```

3. **View attendance log**
    Attendance records will be saved in `Attendance.csv`.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-username/face-recognition-attendance-system](https://github.com/your-username/face-recognition-attendance-system)
