# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:
### Register Number: 
i) #To Read,display the image
```
  import cv2
img = cv2.imread('wol.webp', 1)
cv2.imshow('2122222300530_jeeva', img)
cv2.waitKey(0)

```
ii) #To write the image
```
import cv2
img = cv2.imread('wol.webp', 1)
new_image = cv2.imwrite('wol.webp', img)
cv2.imshow('212222230053_Jeeva', img)
cv2.waitKey(0)


```
iii) #Find the shape of the Image
```python3



```
iv) #To access rows and columns

```python3



```
v) #To cut and paste portion of image
```python3



```

## Output:

### i) Read and display the image

<br>
<br>

### ii)Write the image

<br>
<br>

### iii)Shape of the Image

<br>
<br>

### iv)Access rows and columns
<br>
<br>

### v)Cut and paste portion of image
<br>
<br>

## Result:
Thus the images are read, displayed, and written successfully using the python program.
