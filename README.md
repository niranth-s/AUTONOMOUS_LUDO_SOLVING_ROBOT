# PIXELATE_TECHNEX2019


-Winning solution of Pixelate -an image processing event ,with a hardware implementation for a ludo like maze  


Problem Statement:
                  Pixelate of Technecx2019 ,expected us to develop a robot for playing a ludo like game using the live feed from a over head web cam fead.The detailed PS:(https://github.com/lok-i/PIXELATE_TECHNEX2019/blob/master/Robonex_Pixelate.pdf).
                                                           
                                                           
Our Solution:
 
• We used OpenCV for the shape detection and colour detection and then used it to get to the nearest shape as           given out by the die roll.
• Then an optimal graph/path was plotted to get the optimal trajectory ,connecting the centroids of all the shapes     along the way to the destination shape.
• Once the path was recieved we used PID to make our robot to follow the line conecting all this dots.Individual PID   parameters were used to make the robot to go straight and as well take sharp 90 degree turns.
 
Our Final Run:
 [![Watch the video](Images/Demo.png)](https://www.youtube.com/watch?v=dD-m3eNNoEc)
 
Background processing:
![ScreenShot](https://github.com/lok-i/PIXELATE_TECHNEX2019/blob/master/Images/ScreenShot.jpg)

Robot Used:
![robot](https://github.com/lok-i/PIXELATE_TECHNEX2019/blob/master/Images/robot_used.jpg)
