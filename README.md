# 🚗 SafeDrive: Pothole & Speed Breaker Detection  

SafeDrive is a deep learning-based application that detects potholes and speed breakers from images and videos using the YOLO (You Only Look Once) object detection model. This project is developed using Streamlit for the user interface and OpenCV for image and video processing.  

## ✨ Features  
- 📸 Image Detection: Upload an image, and the system will detect potholes and speed breakers with bounding boxes.  
- 🎥 Video Detection: Upload a video, and the system will process each frame to identify potholes and speed breakers, generating a downloadable processed video.  
- 🚀 Real-Time Object Detection: Uses a pre-trained YOLO model to accurately identify road hazards.  
- 📂 User-Friendly UI: Simple interface built with Streamlit for easy image and video uploads.  

## 🛠 Technologies Used  
- Python  
- Streamlit (for web interface)  
- OpenCV (for image and video processing)  
- YOLO (Ultralytics) (for object detection)  
- PIL (Pillow) (for handling images)  
- Tempfile (for handling video processing)  

## 📌 How It Works  
1. Upload an Image or Video via the Streamlit interface.  
2. The YOLO model processes the input to detect potholes and speed breakers.  
3. Detected objects are marked with bounding boxes and confidence scores.  
4. For videos, the processed output is saved, and a download link is provided.

## 🔧 Installation & Usage  

### 1. Clone this repository:
bash
git clone https://github.com/your-repo/safedrive.git
cd safedrive


### 2. Install dependencies:
bash
pip install streamlit opencv-python ultralytics pillow numpy


### 3. Run the Streamlit app:
bash
streamlit run app.py


### 4. Upload an image or video and get real-time pothole and speed breaker detection.

## 📢 Notes  
- Ensure that the YOLO model file (best.pt) is available in the project directory.  
- The processed video will be available for download after detection.  

## 🎯 Future Enhancements  
- Adding real-time video stream detection.  
- Improving model accuracy with a custom-trained dataset.  
- Extending detection capabilities to more road hazards.
