# invisibility-cloak
This project uses Python and OpenCV to create an "Invisibility Cloak" effect, similar to what you see in Harry Potter movies.
Bring a little magic to life with this fun computer vision project! Inspired by Harry Potter’s legendary invisibility cloak, this Python script makes red-colored objects "invisible" on camera by replacing them with the background.

🔍 How It Works
Captures the static background (without you in the frame)

Detects red color in real-time using HSV color space

Replaces the red areas with the background to create the "invisible" effect

🛠 Tech Stack
Python

OpenCV

NumPy

📸 Demo
Try wearing a red cloth and watch yourself vanish in the live webcam feed like magic!

🧪 Features
Real-time video processing

Color detection with HSV masking

Background subtraction

Morphological operations to clean noise

▶️ Run the Code
pip install opencv-python numpy
python invisibilityCloak.py
Make sure to stay out of the camera view for the first 5 seconds while it captures the background.

🎨 Customize
Change the color to make any object disappear just tweak the HSV ranges in the code.

✨ Inspiration
This project was inspired by the Harry Potter series and is a cool way to explore OpenCV basics!
