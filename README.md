# Drowsiness Detection

This project aims to implement a **Drowsiness Detection System** that can monitor a person's eyes and alert them if they are drowsy. This system can be used to prevent accidents caused by drowsy driving or any other activity requiring constant attention.

## Features

- Real-time detection of drowsiness using a webcam.
- Alerts the user when drowsiness is detected.
- Built using **computer vision** techniques and **machine learning**.
- Easy to set up and use.

## Technology Stack

- **Language:** Python (primarily using Jupyter Notebook for implementation)
- **Libraries:** 
  - OpenCV (for image processing)
  - dlib (for facial landmark detection)
  - NumPy (for numerical computations)
  - imutils (for image manipulation)
- **Tools:** Jupyter Notebook for development and visualization.

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/Pranav03Nair/Drowsiness-Detection.git  
   cd Drowsiness-Detection
   ```

2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Ensure you have a webcam connected to your system.

## Usage

1. Open the project in Jupyter Notebook:  
   jupyter notebook  

2. Run the notebook step by step to execute the drowsiness detection code.

3. The webcam will start, and the system will monitor your eyes for signs of drowsiness. If drowsiness is detected, an alert will sound.

## How It Works

- **Eye Aspect Ratio (EAR):** The system calculates the Eye Aspect Ratio using facial landmarks to determine if the user's eyes are closed for a prolonged period.
- **Thresholding:** If the EAR falls below a certain threshold for a specified duration, the system triggers an alert.
- **Real-time Processing:** The system processes video frames in real time to ensure continuous monitoring.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- OpenCV and dlib communities for the robust libraries.
- Tutorials and research on Eye Aspect Ratio for drowsiness detection.

---

Feel free to explore, modify, and extend this project as needed!
