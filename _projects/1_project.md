---
layout: page
title: Autonomous Aerial Landing of Quadcopter
description: Proof-of-concept simulation of a quadcopter autonomously landing on a moving carrier ship using analytical trajectory planning and adaptive control.
img: assets/img/275_BlockDiagram.png
importance: 1
category: work
related_publications: false
---

In this project, we developed a MATLAB/Simulink proof-of-concept for autonomous aerial landing of a quadcopter on a moving carrier ship. An analytical trajectory generator produces dynamically feasible, fast approach paths, while an adaptive Linear Quadratic Regulator (LQR) controller—fed by a Kalman filter state estimator—ensures precise reference tracking and flight stability throughout the maneuver.

Key highlights include:
- **Trajectory Planning**  
  A real-time, model-based algorithm computes intercept trajectories without the computational overhead of MPC.  
- **Adaptive Control & Estimation**  
  Full-state feedback via a Kalman filter and an LQR controller adapts to disturbances and nonlinearities.  
- **Simulation Framework**  
  Carrier and quadrotor dynamics, sensor noise, ground effects, and rotor models are integrated into a cohesive simulation environment.

This project was completed as the final group project for the MAE 275 course on Guidance Navigation and Control of Unmanned Aerial Systems taught by Prof. Zhaodan Kong at UC Davis. My project partners were [Meridian Haas](https://www.linkedin.com/in/meridian-haas-67a07b228/) and [Zane Hays](https://www.linkedin.com/in/zane-hays-537577240/).