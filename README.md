# face-dection-using-open-cv
Explanation Of The Code
At the beginning of the code, we have included header files that are used in our functions.

1. Then, we have declared the function to detect the face in the video/camera with the necessary arguments.

2. After this, we have defined our main function, in which we are capturing the video, converting it to its individual frame, and at last, calling our detect face function to draw a circle over the detected face.

3. Then, we have defined our detect face function, in which we are converting the frames of the video to grayscale using the cvtcolor() function.

4. Then, we resize each frame and detect the faces using a cascade classifier.

5. After this, we draw circles around the detected face using the cvround and circle function.

6. At last, we use the imshow() function to display the detected face.
