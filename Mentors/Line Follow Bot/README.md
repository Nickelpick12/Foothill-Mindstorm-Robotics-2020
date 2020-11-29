# Line Follow Bot
This explains how to code a bot to follow a line
## Resources
- Here is a video that explains the topic well. --> [How to make Robot Follow a Line - EV3 Classroom](https://www.youtube.com/watch?v=6hzP1lOtSV4). My code is based on this video with a few changes.
## The Bot     (Note) The LDD file has not been added yet.
In this folder there should be a [Lego Digital Designer](https://www.lego.com/en-us/ldd) file showing a example of a compatable robot. The importal points about it are:
- The color sensor is only a cm or so from the floor.
- (Note) The sensor is usally in the middle of the robot because most light is blocked out by then. Diffrent lighting condations can effect the sensor.
- The sensor has to be plugged into a numbered port. In the example code it is plugged into port 3.
## The Code
Here i'll explain the code.
1. Everything happens when the program starts.
2. We set the drive moters to Port B and Port C. (Note) You change this based on your bot.
3. The moter are set to hold there position vs them rolling freely when there stopped.
4. We contenue to drive until moter B rotates 6 times.
5. We update the drive direction and make it move at 10% speed.
6. We stop moving after we are done driving.
7. We stop the program.
## More
If you have anymore questions, ask a mentor!