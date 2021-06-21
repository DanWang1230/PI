# PID Controller

## Describe the effect each of the P, I, D components had in your implementation
* P component: Increasing Kp will cause the system to react more quickly, but also to overshoot more.
* I component: This component helps reduce steady-state error, but makes the system more oscillatory. 
* D component: This component adds damping to the system, thereby decreasing overshoot. 

## Describe how the final hyperparameters were chosen.
Based on the Kp, Ki, and Kd values from the lecture, I manually tweaked the hyperparameters. Especially, the Ki value is kept small to reduce settling time and overshoot.