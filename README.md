

# Image Capture and Video Processing Using OpenCV

---

## Aim

To write a Python program using OpenCV to capture an image from the webcam and perform the following operations:

1. Save a captured frame as a JPG image
2. Display the live video stream
3. Display the video after resizing the frame
4. Rotate and display the video

---

## 🛠️ Software Used

- Anaconda – Python 3.7 or above
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- Matplotlib (`matplotlib.pyplot`)
- IPython Display (`clear_output`)

---

## ⚙️ Algorithm

### Step 1:
Import the required libraries: OpenCV, Matplotlib, IPython display utilities, and time.

### Step 2:
Initialize the webcam using `cv2.VideoCapture(0)`.

### Step 3:
Capture a single frame and save it as `captured_frame.jpg` using `cv2.imwrite()`.

### Step 4:
Read the saved image and display it using Matplotlib.

### Step 5:
Capture multiple frames from the webcam and display them as a live video stream.

### Step 6:
Resize each frame using `cv2.resize()` and display the resized video.

### Step 7:
Rotate each frame by 90° clockwise using `cv2.rotate()`.

### Step 8:
Display the rotated video frames.

### Step 9:
Release the webcam after completing all operations.

---

## 💻 Program

### Developed By:
**Name:** Aaron I
**Register No:** 212223230002

---

## Output

### i) Save Captured Frame as JPG

<img width="421" height="317" alt="image" src="https://github.com/user-attachments/assets/e5f3f4b5-a361-43f8-bd2b-2b87b2b75a17" />


### ii) Display Live Video

<img width="457" height="297" alt="image" src="https://github.com/user-attachments/assets/2994ef25-93bc-440e-9f09-f5b892cb9c78" />


### iii) Display Resized Video

<img width="383" height="317" alt="image" src="https://github.com/user-attachments/assets/e4e3d886-e672-4627-a659-818f7a7dcc5b" />

### iv) Rotate and Display Video

<img width="322" height="303" alt="image" src="https://github.com/user-attachments/assets/24f7cd21-8065-473a-a276-0582f16704a1" />


---

## Result

Thus, the webcam image was successfully captured and saved as a JPG file. The live video stream was displayed, resized, and rotated using OpenCV and Matplotlib.

---
