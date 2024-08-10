# 🖌️ Paint App

Welcome to the **Paint App** created by **Brave Boy Codes**! This application uses OpenCV, NumPy, and MediaPipe to let you draw on a canvas using your webcam. Below is a guide on how to use the code and troubleshoot common issues.

## 🚀 How to Use

1. **Install Dependencies:**

   Make sure you have Python installed on your system. Install the required packages by running:

   ```bash
   pip install opencv-python numpy mediapipe
Run the Application:

Execute the script using Python:

bash
Copy code
python airboard.py
This will open two windows:

"Output": Displays the live video feed from your webcam.
"Paint": Shows the paint canvas where you can draw.
Using the App:

Draw: Use your index finger to draw on the canvas. The app detects your hand gestures and allows you to draw in the selected color.
Select Color: Tap the colored rectangles at the top of the canvas to switch colors.
Clear Canvas: Tap the "CLEAR" button to reset the canvas.
🛠️ Required Libraries
To run this application, you need to have the following Python libraries installed:

OpenCV: For handling video capture and image processing.
NumPy: For numerical operations on images.
MediaPipe: For hand tracking and gesture recognition.
You can install these libraries using:

bash
Copy code
pip install opencv-python numpy mediapipe
⚠️ Common Issues and Solutions
Error: NoneType object has no attribute 'shape'

Cause: This error occurs if the webcam frame is not properly captured.

Solution: Ensure that your webcam is connected and functional. Verify that other applications can access your webcam. Restart your computer if needed.

Warnings Related to TensorFlow Lite

Cause: These warnings are related to TensorFlow Lite's internal processing and do not impact the functionality of the app.

Solution: These warnings can generally be ignored as they do not affect the core features of the drawing application.

💡 Tips
Color Selection: You can switch between colors by tapping on the colored areas at the top of the screen. The colors are: Blue, Green, Red, and Yellow.
Drawing Accuracy: Ensure your hand is properly detected for accurate drawing. The app uses hand landmarks to determine drawing positions.
📸 Screenshots

📝 More
Customizations: Feel free to modify the code to add more colors or change the drawing settings.
Extensions: You can integrate additional features such as saving drawings or adding more shapes.
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

Made with ❤️ by Brave Boy Codes

markdown
Copy code

### Instructions:
- **Replace** `path-to-your-screenshot.png` with the actual path to your screenshot or remove the screenshot section if not applicable.
- **Ensure** you have a `LICENSE` file in your project if you're referencing it.

This file provides clear instructions for running the application, details about required libr
