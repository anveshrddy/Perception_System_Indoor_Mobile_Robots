# Perception_System_Indoor_Mobile_Robots
A modular ROS2-based real-time perception system for indoor mobile robots, integrating object detection, monocular depth, and 3D localization for autonomous navigation.

## Objectives
- A robot that can navigate autonomously in an static indoor environment

## Perception inputs
- Camera feed for monocular depth estimation
- Camera input for obstacle detection

## Perception outputs
- 3D localization of the robot
- Navigation
- Obstacle detection


## Questions for myself
- What are the specs I need to care about?
- What is the plan?
- What are the latest methods out there?

### Specs
- ROS2 for IPC
- Start with Static scene
- Dataset to use: <TBD>
- Resolution of the camera is based on the data we get for now. Establishing the system should be high priority.
- Make sure Git is utilized. Commits should be small and meaningful.
- Best software practices have to be followed
- Production ready code is expected
- For each concept, I need to ensure that I know each line of code that I write
- Quality over Speed
- All deep learning models that are finetuned have to be documented
- LOGS ARE IMPORTANT
- I need a heartbeat
- Infinite visual world is expected so that the robot can navigate in an infinite environment.
- Assume a car-like robot
- All alerts: Impossible Obstacle, Person in the way, etc. should be communicated instantly.
- Idea: Should use audio to start/stop the robot
