 **Task 02: Connected Component Labeling for Object Counting**

**Roll Number:** 2023-SE-06

### **Prompt**

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

The objective of this task is to detect and count distinct objects in a given image using **Connected Component (CC) labeling** and create a colorful visualization of the objects for better understanding of object segmentation.

---

## **Methodology / Approach**

1. Upload the colored image in Google Colab using `files.upload()`.
2. Read the image with `cv2.imread()` and convert it from **BGR to RGB**.
3. Convert the RGB image to **Grayscale**.
4. Apply **Otsu's thresholding** to generate a **Binary** image.
5. Perform **Connected Component labeling** to detect and count objects.
6. Generate a **colorful visualization**, assigning a random color to each object.
7. Display the **Original**, **Binary**, and **Connected Component Labeled** images using Matplotlib with titles and axes turned off.

---

## **Results / Observations**

* Total number of objects detected is printed, excluding background.
* Binary image effectively separates objects from background.
* Colorful visualization differentiates each connected object, aiding in visual analysis.
* Works correctly for any uploaded colored image in Google Colab.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2)** – image reading, conversion, thresholding, connected components
* **NumPy (np)** – array operations for label visualization
* **Matplotlib (plt)** – visualization
* **Google Colab** – image upload and execution

---
