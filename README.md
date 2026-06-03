# MSMS_Project
Modeling and Simulation of Mechatronic Systems' final project.

This repository contains a dynamic model and control simulation for the 6-DOF UR-5 Robot Manipulator, developed using 20-sim. 

The project focuses on accurately modeling the physical and mechanical properties of the robot's architecture.  

Key Features:

Detailed Mechanical Modeling: Includes the complete dynamics of the robot's links and joints, accounting for 3D gravity effects, Euler equations, and homogeneous transformations.  

Harmonic Drive Dynamics: Features a highly detailed model of the harmonic drives, incorporating non-linear torsional stiffness (modeled in three distinct linear sections), system inertia, and combined viscous and Coulomb friction.  

PID Control: Implements a custom PID controller with anti-windup and derivative gain limitation to accurately guide the manipulator's six joints to a desired final configuration.  

System Simulation: The system is built using a bond graph and block diagram methodology to simulate the multi-domain physical interactions and visualize the robot's 2D/3D kinematic movements.  
