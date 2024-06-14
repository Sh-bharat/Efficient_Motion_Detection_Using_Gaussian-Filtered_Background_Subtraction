---

# Efficient Motion Detection Using Gaussian-Filtered Background Subtraction

This Python script implements a real-time motion detection system using Gaussian-filtered background subtraction to reduce noise and highlight motion.

## Overview

The system captures video frames from a webcam, applies Gaussian blur to reduce noise, computes differences between frames, and uses thresholding to detect and display motion areas in real-time.

## Features

- **Real-Time Detection**: Processes and displays motion from live video.
- **Noise Reduction**: Uses Gaussian blur to minimize noise.
- **Dynamic Thresholding**: Isolates significant motion changes.

## Requirements

- Python 3.x
- OpenCV (`cv2`) library

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/motion-detection-gaussian.git](https://github.com/Sh-bharat/Efficient_Motion_Detection_Using_Gaussian-Filtered_Background_Subtraction.git)
   cd Efficient_Motion_Detection_Using_Gaussian-Filtered_Background_Subtraction
   ```

2. **Install dependencies:**
   ```bash
   pip install opencv-python
   ```

## Usage

1. **Run the script using any python enviroment**
   

2. **Operation:**
   - The script captures video from the default webcam.
   - Press the 'Esc' key to exit.

## Code Description

- **`apply_filters(frame)`**: Converts a frame to grayscale and applies Gaussian blur.
- **`threshold_and_difference(first_gaussian_blur, gaussian_blur)`**: Computes frame differences and applies thresholding.
- **Main Loop**: Captures and processes frames continuously, updating displayed results.

## Example Output

https://github.com/Sh-bharat/Efficient_Motion_Detection_Using_Gaussian-Filtered_Background_Subtraction/assets/133742551/f8cec005-87b1-4e30-90da-2ef1aa9840a2



## License

This project is licensed under the MIT License.

## Contact and Contributions

For any inquiries or to contribute to the project, please feel free to:
- **Open an Issue**: [Issues](https://github.com/Sh-bharat/Machine_Learning_for_Medical_Image_Analysis-Brain_Tumor_Classification/issues)
- **Submit a Pull Request**: [Pull Requests](https://github.com/Sh-bharat/Machine_Learning_for_Medical_Image_Analysis-Brain_Tumor_Classification/pulls)

---
