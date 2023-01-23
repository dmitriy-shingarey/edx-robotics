# Week 3: Robot Arms - Forward Kinematics

Robot Arms Introduction, Kinematic Chains, Forward Kinematics: URDF, Forward Kinematics: Analytical Methods, DH Parameters, Forward Kinematics:DH Examples, Project 3 released

## Kinematic Chains and Forward Kinematics

### Kinematic Chain

Kinematic chain is a sequence of joints and links. By modeling, a joint usually have a single degree of freedom.

![kinematic chain](pics/kinematic_chain.png)

There are revolute and prismatic joint:

![2 types of joints](pics/2_types_of_joints.png)

### Forward Kinematics

Given the specific values for all the joints where is the end effector end up in space, considering where every link of the robot is (e.g. to avoid obstacles).

Attach a coordinate frame to each link, including base and end effector. What is the transform from base coordinate frame to the end effector coordinate frame.

Convention used in this course: joint Ji is followed by the link Li. At the end of the link Li is the coordinate frame i is attached. Ji is precceded by link Li-1.

![forward kinematics](pics/forward_kinematics.png)

 It gives following:

* n joints
* n + 1 links
* n + 1 coordinate frames
* Ji moves Li
* coordinate frame {i} is at the tip of the Li
* coordinate frame {n} is at end effector

There are different conventions. So what is the transform from the base to the end effector ${}^{b}T_{ee}$?

## Forward Kinematics: URDF notation

## Forward Kinematics: DH Examples

## DH Notation Example: 2-link Planar Robot

## DH Notation Example: SCARA Robot

## Kinematic examples: 6DOF and 7DOF robots
