# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
open the robot analyzer software.
select the robot and its degrees of freedom.
change the values with the link length whenever necessary.
simulate the model for forward kinematics.
pick the graph between the link and the joints.
update the DH parameters of the link configuration and endeffector configuration.




### SIMULATION :
 ### 6DOF
 ### KUKA KRS ARC ROBOT
![ana2](https://user-images.githubusercontent.com/94175324/174300290-bb1c5289-3231-4416-b40b-4f0188983d55.png)
![an1](https://user-images.githubusercontent.com/94175324/174300266-d767c753-5c38-4238-b398-41c3793a6601.png)
### 4DOF
 ![4](https://user-images.githubusercontent.com/94175324/174301500-fbe2f00a-592b-4588-9922-977d3100e394.png)
![4 2](https://user-images.githubusercontent.com/94175324/174301605-9585253f-ba7d-4150-a90a-21b4a94301d0.png)

 
 ### PLOT :
 ### 6DOF GRAPH
 ![ana](https://user-images.githubusercontent.com/94175324/174300224-d8616eae-3e32-4982-9426-ec60ea2092cc.png)
### 4DOF GRAPH
![4 1](https://user-images.githubusercontent.com/94175324/174301744-3a6b0fd9-c736-4c15-a533-2d92dee074ab.png)


 # RESULT: 
Thus the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
