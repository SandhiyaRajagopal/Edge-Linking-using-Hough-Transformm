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
![image](https://github.com/user-attachments/assets/ca587491-edcb-4b95-9bc7-49aec18bdabf)
![image](https://github.com/user-attachments/assets/50fa30e1-a281-4fca-bc4c-7eed65a236c1)


### Canny Edge detector output
![image](https://github.com/user-attachments/assets/5b018b89-24d8-4b0a-923e-b5821d7ad8bd)


### Display the result of Hough transform
![image](https://github.com/user-attachments/assets/df4c4c4b-3b3a-45fd-a8f9-6495b889e0e4)

## Result:
Hence, a python program to detect the lines using Hough Transform is implemented and executed.
