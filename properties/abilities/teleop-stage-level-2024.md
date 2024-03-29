# teleop-stage-level-2024

## Definition
The teleop-stage-level-2024 ability represents the level of stage climb of the robot at the end of the teleoperated period of the match.

## Values
This property stores an integer (0 - 4) based on the level of stage climb.
- 4: onstage in harmony with two other robots
- 3: onstage in harmony with one other robot
- 2: onstage
- 1: parked
- 0: none

## Examples
- 4
- 3
- 2
- 1
- 0

## Design Recommendation
This property can be implemented as a dropdown menu, where the user can select the stage climb level.
