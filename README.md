# Wisconsin_Autonomous

![answer](https://user-images.githubusercontent.com/123520788/221480807-f0b733b9-7689-4881-9bda-6a10029a6258.png)




Methodolgy - 
Download the red.png
resize the image
identify the cones by contouring the red color
identified the cones by height to width ratio, and area
drew lines using slope and endpoints of the cones on either sides

Tried these - 
I tried identifying the cones using area only first but it did not work since the area of contours on th door were in the similar range of the area of the cones. 
I also tried using only x and y coordinates to identify the cones but that didnt work since the x coordinate of the first cone is out of range with other cones and if i include the first cone, i had to include the door contours as well. 
Tried using centroids of the cones to draw the lines first but there was some unknown mistake so i couldnt complete it successfully. Instead used slope and endpoints to draw the lines. 

Libraries used - cv2, numpy and matplotlib
