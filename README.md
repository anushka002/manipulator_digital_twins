# manipulator_digital_twins
This Repository contains files for the digital twins of Robotic manipulators simulated using MATLAB as a part of RAS-545 course at ASU.

1. **MyCobot 280** (Lab 1)
   _Digital Twin :-_
   Contains lab report on the MyCobot 280. It includes an introduction to the MyCobot 280, a detailed setup guide, a description of the lab process,
   caliberation and control of robot arm, and a conclusion summarizing the learning experience. A demonstration video has also been submitted as part of the assignment.
   
2. **MyCobot 280** (Lab 2)
   _Digital Twin :-_
   Contains the homogeneous transformation matrices for the MyCobot 280 M5, performing symbolic matrix multiplication in MATLAB to compute
   Final Homogeneous Transforma matrix, substituting joint angles for the end-effector's position and orientation,
   and comparing MATLAB results with pymycobot outputs. All tasks are documented, and a video demonstration is included.
   
4. **MyCobot Pro 600** (Lab 3)
   _Digital Twin :-_
   Contains the kinematic diagram and homogeneous transformation matrices for MyCobot Pro 600.
   Forward kinematics was solved in MATLAB to determine the end-effector position for given joint angles. The CAD model of the robot was successfully imported into MATLAB with joints added,
   and forward kinematic analysis was performed using Simscape and the Robotics Toolbox. The angles collected from the MyCobot Pro 600 were validated to ensure
   the digital twin reached the same end-effector position. A 3-minute video demonstrating MATLAB simulation, and robot validation has been created.
   https://github.com/Robotics-and-Dynamical-Systems-Lab/RAS545/blob/fall2024/Lab3/instructions.md
   
5. **Fanuc LR 200iD 14L** (Assignment 3)
   _Digital Twin :-_
   Forward and inverse kinematics were derived, and the homogeneous transformations were calculated.
   MATLAB and Simulink were used to load the predefined FANUC 200iD robot model. Workspace analysis was performed using the Robotics Systems Toolbox,
   and both forward and inverse kinematics were implemented as per the requirements.

9. **MyCobot Pro 600** (Lab 4)
   _Digital Twin :-_
   Contains derivation of homogeneous transformations, creating a digital twin,
   and programming of robot using socket programming to execute commands. The AI kit camera was connected, ArUco markers were placed in the workspace,
   and the robot path was planned and executed in a straight line between the markers, verified through the digital twin.
   https://github.com/Robotics-and-Dynamical-Systems-Lab/RAS545/blob/fall2024/Lab4/instructions.md

11. **MyCobot Pro 600** **(FINAL PROJECT)**
   The project focuses on using the MyCobot Pro 600 to solve a 4x4 rectangular maze with the following steps:

    1. **Maze Generation**: 
       - Use the maze generation tool to create a 4x4 maze.
       - Set the maze dimensions and scale to fit within the robot’s workspace.
    
    2. **Maze Solving**: 
       - Develop an algorithm to solve the maze by processing an image of the maze.
       - Convert the solution path from pixel values to physical waypoints for the robot.
    
    3. **Digital Twin Path Planning**: 
       - Build the digital twin of the MyCobot Pro 600 to simulate forward and inverse kinematics.
       - Plan the robot’s path to move through the maze based on the waypoints.
       - Ensure the robot moves accurately to each waypoint using realistic joint angles.
    
    4. **Execution and Recording**: 
       - Set up the AIKit camera and robot for socket programming.
       - Write code to navigate the waypoints, ensuring the robot follows a straight line path.
       - Record a video showing the robot’s movements in both the digital twin and real-world execution.
    
    The project emphasizes path planning, image processing, and ensuring the robot follows the maze solution efficiently and accurately.
    The demonstration should show that the robot’s movements align with the digital twin and maintain a safe distance from the maze.
    https://github.com/Robotics-and-Dynamical-Systems-Lab/RAS545/blob/main/Final_Project/instructions.md
    
