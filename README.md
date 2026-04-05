# Counting-Cars
Count how many cars have pass by
A. Your approach to solving the task.
For my approach is using "YOLOv8" to identify cars. Then each deteched object will be assigned with an ID. The objects are match frame to frame based on proximity. Then there will be a vertical line is place oin the middle of the frame then when a car have crosses the line and it will only count once when cross.
B. Technologies and tools used.
-Ultralytics YOLOv8.
-Google colab(Because it can run faster).

C. Steps to reproduce the results.
1. First have to download the mp4 video that is given.
2. Then upload the mp4 to google colab.
3. Change the video path if needed (Can find the file path from the "file" in Google Colab).
4. After that we will have to install the dependencies "pip install ultralytics opencv-python-headless filterpy".
5. Run the Script.
6. There will be a video output where u can see the counting in action.
