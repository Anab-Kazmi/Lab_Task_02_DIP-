# **Task 02: Connected Component Labeling for Object Counting**

**Roll Number:** 2023-SE-06

### **Prompt**

`2023-SE-06_Lab_Task_02_DIP-`

*"Write a Python program using OpenCV, NumPy, and Matplotlib to do the following in Google Colab:

* Allow the user to upload any colored image.
* Convert the image to grayscale and then to a binary image using Otsu's thresholding.
* Apply Connected Component labeling to detect and count all objects in the binary image.
* Display the total number of objects detected.
* Create a colorful visualization of the connected components (each object in a different random color).
* Display the Original Image, Binary Image, and Connected Component Labeled Image using Matplotlib in a clear layout with proper titles and axes turned off.
* Ensure the code is fully compatible with Google Colab and runs without errors."*

---

## **Objective**

The objective of this task is to detect and count distinct objects in a given image using **Connected Component (CC) labeling**. Additionally, the task creates a colorful visualization of the detected objects to better understand object segmentation in binary images.

---

## **Methodology / Approach**

1. User uploads a colored image in Google Colab using `files.upload()`.
2. The image is read using `cv2.imread()` and converted from **BGR to RGB** format.
3. Converted the RGB image to **Grayscale** using `cv2.cvtColor()`.
4. Applied **Otsu's thresholding** to convert the Grayscale image into a **Binary** image.
5. Used **Connected Component labeling** (`cv2.connectedComponents`) to detect and count objects in the binary image.
6. Generated a **colorful label visualization**, assigning each object a random color for better differentiation.
7. Displayed the **Original Image**, **Binary Image**, and **Connected Component Labeled Image** using Matplotlib with proper titles and axes turned off.

---

## **Results / Observations**

* Total number of objects detected is printed, excluding the background.
* Binary image effectively separates objects from the background.
* Colorful visualization clearly differentiates each connected object, making segmentation and counting intuitive.
* The workflow works seamlessly in Google Colab for any uploaded colored image.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2):** Image reading, conversion, binary thresholding, connected components
* **NumPy (np):** Array manipulation for label visualization
* **Matplotlib (plt):** Visualization of original, binary, and labeled images
* **Google Colab:** Image upload and execution environment

---
