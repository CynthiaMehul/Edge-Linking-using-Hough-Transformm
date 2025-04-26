# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Import all the necessary modules for the program.

### Step2:
Load a image using imread() from cv2 module.

### Step3:
Convert the image to grayscale.

### Step4:
Using Canny operator from cv2,detect the edges of the image.

### Step5:
Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.

## Output

### Input image and grayscale image

![image](https://github.com/user-attachments/assets/a76a2cb8-a21b-491a-b425-905e8d3db8b0)

![image](https://github.com/user-attachments/assets/e05b7276-57c8-459e-a01a-b69e9dd2cbfc)

### Canny Edge detector output

![image](https://github.com/user-attachments/assets/6b196d13-935d-4daf-8d6f-0fd6d73e7cef)

### Display the result of Hough transform

![image](https://github.com/user-attachments/assets/87c4c2fd-533f-4ac9-b970-364f2876cf51)

## Result:
Hence, a python program to detect the lines using Hough Transform is implemented and executed.
