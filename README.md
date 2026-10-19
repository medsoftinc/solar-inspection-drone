# Solar Inspection Drone

An autonomous drone that inspects solar farms and detects faulty panels using onboard AI.

The drone flies over a solar farm in a lane-by-lane pattern, detects broken or dirty panels with a camera and an AI model, marks the location of each fault on a map, and generates an inspection report. All AI inference runs on the drone itself (Edge AI).

## Tech Stack
ROS 2 Lyrical · PX4 · Gazebo · Python · OpenVINO · YOLO

## Roadmap
- [ ] Module 0: Setup and first takeoff in simulation
- [ ] Module 1: Controlling the drone from code
- [ ] Module 2: Lane-by-lane scan route
- [ ] Module 3: Simulated solar farm
- [ ] Module 4: AI fault detection model
- [ ] Module 5: Fault localization
- [ ] Module 6: Automatic map and report
- [ ] Module 7: Real drone hardware
- [ ] Module 8: Porting the software to the real drone
- [ ] Module 9: Field test
