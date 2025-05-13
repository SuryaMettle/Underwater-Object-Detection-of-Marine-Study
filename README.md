Underwater Object Detection of Marine Study using OpenCV This project leverages OpenCV to detect and highlight underwater objects in marine environments by segmenting them from water regions based on color filtering in the HSV (Hue, Saturation, Value) space. It is a valuable tool for marine research, visual inspection, and object monitoring beneath the water surface.

📌 Features Detects underwater objects from images using color thresholds.

Suppresses water background (blue-green shades).

Highlights detected objects in yellow.

Visual comparison between original and processed images.

🛠 Technologies Used Python 3.x

OpenCV

NumPy

Pillow

Google Colab (for image upload and display)

🚀 Getting Started 📁 Clone the Repository bash Copy Edit git clone https://github.com/SuryaMettle/Underwater-Object-Detection-of-Marine-Study/new/main?readme=1 🔧 Install Dependencies bash Copy Edit pip install opencv-python numpy pillow 💡 Run the script in Google Colab for built-in image upload and display support.

🖼 Usage Upload an underwater image when prompted.

The script filters water (blue-green regions).

Objects are segmented and highlighted in yellow, while water is shown as black.

The original and processed images are displayed side by side.

✅ Conclusion This project presents a simple yet effective method for underwater object detection using image processing techniques in OpenCV. The approach involves converting the input image to HSV color space, where blue-green shades typical of water are isolated using thresholding. A binary mask is created to differentiate between water and non-water regions. By inverting this mask, objects present in the water (such as rocks, debris, or marine species) are identified.

The final output highlights these detected objects in yellow against a black background (representing water), providing a clear and focused visualization. This technique supports marine research by making it easier to study submerged objects, and it can be extended to real-time analysis in underwater robotics, marine exploration, or environmental monitoring.

📂 File Structure perl Copy Edit Underwater-Object-detection-of-marine-study-using-Open-CV/ │ ├── MAIN.py # Main script for object detection ├── README.md # Project documentation └── Outputs # Any sample images/output

🤝 Contributing Feel free to fork this repository, make enhancements, and create a pull request. Contributions are welcome!
