# stability

## Definition
The stability rating represents a subjective evaluation of the stability of the robot during the match.

## Values
This property stores an integer value on a 0-4 scale based on the robot's stability.
- 4: exceptional stablility
- 3: above average stability
- 2: average stability
- 1: below average stability
- 0: poor stability

## Examples
- 4
- 3
- 2
- 1
- 0

## Design Recommendation
This property can be implemented as a 5-star rating indicator, where a user can select anywhere from 1-5 stars (mapped internally on a 0-4 scale). Alternatively, this property could be implemented as a slider from 0 to 4 with a step size of 1.
