# AI-Project -> Emotion Detection
This project is based on using ai to detect emotions 

The emotions detected are Happy, Sad, Angry, Neutral (emotionless)

## To install opencv-python
Use commands:

- To upgrade pip:  ` pip install --upgrade pip`

  - Check pip version: ` pip -V ` 
  
  - Check pip version: ` pip -V `

### Select the correct package for your environment: (SELECT ONLY ONE OF THEM)

### a. Packages for standard desktop environments (Windows, macOS, almost any GNU/Linux distribution)
 Option 1 - Main modules package: ` pip install opencv-python `
 
 Option 2 - Full package (contains both main modules and contrib/extra modules): ` pip install opencv-contrib-python `

### b. Packages for server (headless) environments (such as Docker, cloud environments etc.), no GUI library dependencies
 Option 3 - Headless main modules package: ` pip install opencv-python-headless `
 
 Option 4 - Headless full package (contains both main modules and contrib/extra modules): ` pip install opencv-contrib-python-headless `  (check contrib/extra modules listing from OpenCV documentation)

## To install Tensorflow

TensorFlow is tested and supported on the following 64-bit systems:
- Python 3.8–3.11
- Ubuntu 16.04 or later
- Windows 7 or later (with C++ redistributable)
- macOS 10.12.6 (Sierra) or later (no GPU support)
- WSL2 via Windows 10 19044 or higher including GPUs (Experimental)

### Installing tensorflow 
- Requires the latest pip
  - ` pip install --upgrade pip`
- Current stable release for CPU and GPU
  - ` pip install tensorflow `
- Or try the preview build (unstable)
  - ` pip install tf-nightly `

## Files to be included in the folder of the project
- haarcascade_frontalface_default.xml
- Emotion_Detection.h5

 









