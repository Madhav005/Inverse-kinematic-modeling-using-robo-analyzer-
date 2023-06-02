# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)
![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)
![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)
![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
1. Open the RoboAnalyzer App:![240796492-66def37e-14a5-4b1e-9e9b-d6eb6b45a2a3](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/e7cd288e-96f2-4101-89f6-53b066db8075)

2. Change the DOF to threee:![240796704-40e1f10c-b319-43b0-924d-150f001873de](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/26fd8fb2-6f56-4707-8e32-668dbea322f6)

3. Open Ikin and set parameters:![240797229-345d3fa9-f489-4359-a654-deb01d95b8cb](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/9f3bd1ee-0acd-4651-bba2-251fa22b295e)

4. Click Fkin and play:![240795269-ee5297f5-22b9-4815-92bd-e64c70263c78](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/0ea6a422-60c0-4d5e-a29c-a09315245d5f)

### SIMULATION 
![240795269-ee5297f5-22b9-4815-92bd-e64c70263c78](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/2f6c146c-38b4-48c7-8b4b-901d73d20f42)
  
 ### PLOT 
 Link1:
 ![240795913-e93e95af-b48a-4efc-be66-ea4036e21f74](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/1e8523d7-7243-4ef4-ba78-bc841b02df25)
Link2:
![240795849-df9bc708-8716-4431-95da-4f7fe91c7456](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/83ac7aec-1399-4f0e-9347-0a18a7c15ad1)
Link3:
![240796018-8d5a9788-071a-4aba-9a87-4868ef510970](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/81fb3af0-2498-4ffb-a488-5cf3938c9a07)
Joint1:
![240796116-fd461064-7add-438d-b45b-562046d3536e](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/0bf34757-ff51-4669-ab8a-9ed3b0ea8b16)
Joint2:
![240796187-bf8f62eb-f20c-4ce8-bb4d-a17ff21573bc](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/414453a4-118b-4df4-816e-eee81be039c2)
Joint3:
![240796259-2618db91-2391-403e-9e4b-7d4d88655dc0](https://github.com/Madhav005/Inverse-kinematic-modeling-using-robo-analyzer-/assets/110885274/eccfa100-93fe-4d64-801d-ac85cf351595)

### RESULTS :  
Thus the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given input end effector position has been analysed.
