# Automatic Number Plate Recognition System

## Overview
The **Automatic Number Plate Recognition System (ANPR)** is a computer vision-based project that detects and recognizes vehicle license plates using Python and OpenCV. This system can be used for traffic monitoring, parking management, and law enforcement applications.

## Features
- Automatic detection of license plates from images and video streams.
- Optical Character Recognition (OCR) for extracting plate numbers.
- Preprocessing techniques to enhance image quality.
- Real-time and batch processing capabilities.
- Integration with databases for storing recognized plates.

## Technologies Used
- **Programming Language**: Python
- **Libraries & Tools**:
  - OpenCV (for image processing and plate detection)
  - Tesseract OCR (for text recognition)
  - NumPy & Pandas (for data handling)
  - Matplotlib (for visualization)

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- Tesseract OCR

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Automatic-Number-Plate-Recognition-System.git
   cd Automatic-Number-Plate-Recognition-System
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install Tesseract OCR:
   - Windows: Download from [here](https://github.com/UB-Mannheim/tesseract/wiki)
   - Linux:
     ```bash
     sudo apt install tesseract-ocr
     ```
   - macOS:
     ```bash
     brew install tesseract
     ```

## Usage
1. Run the system on an image:
   ```bash
   python anpr.py --image path/to/image.jpg
   ```
2. Run the system on a video:
   ```bash
   python anpr.py --video path/to/video.mp4
   ```
3. Use a webcam for real-time recognition:
   ```bash
   python anpr.py --webcam
   ```

## Project Structure
```
Automatic-Number-Plate-Recognition-System/

│── ANPR - Tutorial.ipynb  # Jupyter Notebook for step-by-step tutorial
│── README.md          # Project documentation
```

## Results
The system successfully detects and extracts number plates from images and videos. The OCR extracts alphanumeric characters with high accuracy, depending on image quality and preprocessing.

## Future Improvements
- Integrate a real-time alert system for unauthorized vehicles.
- Enhance character recognition using advanced OCR techniques.



## Contact
For any queries or support, contact:
- **Name**: Banaganapalli Sai Pranav
- **Email**: bsaipranav502@gmail.com
- **LinkedIn**: [Your LinkedIn Profile]([https://www.linkedin.com/in/yourprofile](https://www.linkedin.com/in/sai-pranav-banaganapalli-532022231/))


