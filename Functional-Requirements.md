# Functional Requirements

## Joint Ranges of Motion
A guideline to the ranges of motion in each joint of the hand, these values are not necessarily accurate to the average human hand, but are approximations useful for design.
Total DOF according to these guidelines is 24/26:

-4 per finger (16)

-4/5 for thumb depending on modelling of CMC joint

-1/2 for CMC joints in palm depending on if these are independent or geared together

-2 for wrist

### Interphalangeal Joints (IP)
The interphalangeal joints of the hand can be modelled mechanically as a simple, single axis hinge. 

##### Distal Interphalageal Joints
90° flexion, 30° hyperextension
##### Proximal Interphalangeal Joints
130° flexion
##### Thumb Interphalangeal Joints
90° flexion, 80° hyperextension

### Metacarpophalangeal Joints (MCP)
Metacarpophalangeal joints bridge the gap between the carpal bones and the metacarpals. They are a condyloid style joint with two degrees of freedom, similar to a ball socket joint.

##### Fingers Metacarpophalangeal Joints 
30° total lateral deviation, 40° extension, 90° flexion
##### Thumb Metacarpophalangeal Joints
30° lateral deviation, 80° flexion

### Carpometacarpal Joints (CMC)
The CMC joints connect the carpal section of the hand to the metacarpals.

##### CMC joints in the palm
The fourth and fifth CMC joints (ring and pinky finger) have a ROM of roughly 15° and 30° respectively, on a diagonal rotation axis

##### Thumb CMC joints 
CLARIFICATION NEEDED Thumb CMC is a weird 3-axis saddle joint

### Wrist 
Currently only concerned with proximal joint of the wrist (i.e. flexion/extension, lateral deviation). Assumption is that the turning over of the palm would be actuated from near the elbow joint (as in a real hand).
80° flexion, 70° extension, 40° pinky-side lateral deviation, 25° thumb-side lateral deviation.
