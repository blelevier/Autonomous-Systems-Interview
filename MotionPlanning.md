# Motion Planning Engineer

## Questions

- [Code] Explain the A* search algorithm. What is one way to improve upon this algorithm for usage in real-world scenarios?
- You have a robot on a map with some obstacles on the map. The goal is in the corner of the map. How do you navigate the robot from its current position to the goal?
- Explain some of the different techniques used for global planning (such as at a city map level) vs. micro planning (such as planning on how to go from the entrance of a parking lot to a desired space). Show how you could implement techniques from these levels into one end-to-end algorithm to guide a mobile robot from one distant location to another.
- Explain the concepts behind Deep Reinforcement Learning, and how you would implement such a technique toward Motion Planning. How would you determine the reward functions to use? Would your implementation generalize well towards new, previously unseen environments?
- How do you would generate a desired trajectory over a fixed time horizon for a robot traveling at high speed? Consider what information you would need in order to determine a reasonable trajectory, as well as any additional constraints you may need to consider.
- [Code] Assume you have data of various robot trajectories around your own, in which you would like to build a model to predict the other robots’ behaviors, making sure that your own expensive robot is not damaged by collisions. Your robot does not have the benefit of GPU acceleration. Choose a classification technique in order to learn to predict behaviors, and explain your choice. Then, code an example of how you would build, train and implement this model.
- What is the difference between a data-based approach versus a model-based approach for behavior prediction? Explain the advantages and disadvantages of each, as well as you could implement the separate techniques.
- How can Partially observable Markov decision processes (POMDPs) be utilized in Motion Planning? How does the number of belief states in POMDPs relate to the state space of your robot, and how can that impact the performance or usability of this method in real-world applications?
- [Code] Explain the concepts behind a rapidly-exploring random tree (RRT), and implement an example in code.
- Explain how lattice planning can be used to discretize and simplify the paths through search space. Construct an example of a simple search space to show how this method works.
- Given a vehicle driving on a highway with other cars around it as well as potential stop lights and pedestrian crossings, and assuming perfect information from sensor data, construct a behavior tree/finite state machine for the vehicle's motion.
- [Code] Explain the D* search algorithm (also known as Dynamic A*). What is one way to improve upon this algorithm for usage in real-world scenarios?