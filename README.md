# MazeRunner
Game about escaping from the maze, implemented in Unity3D

# Rules
* Ground
  - Material Desert_sand_sample256
  - Small size scale 2x2x2
  - Medium size scale 3x3x3
  - Large size scale 4x4x4
* Walls
  - Thickness scale X = 0.25
  - Height scale Y = 1.5 (if it is 1 then head of our character is in ceiling and we can see through it)
  - Length scale Free
  - Object is Desert_Temple_SegmentSingle
  - Remember to add Box Collider
  - Remember to turn off Cast Shadows and unmark Receive Shadows
* Ceiling
  - Same as the ground but rotated 
