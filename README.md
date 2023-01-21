# CHI 2023 Publication Repository

This is the corresponding repository for the paper published in ACM CHI 2023: https://doi.org/10.1145/3544548.3580721

Datasets provided here are with the aim of enabling furthure research. Please cite the paper if you use this dataset. Folder names correspond to subject IDs.

The events file includes events.csv recorded by the system and the times.txt file includes events recorded manually.

Explaining the tracking data:

*for all subjects eye gaze data is overridden by head gaze data since we disabled eye tracking.*

- eye gaze origin (Vector3): the point from which the direction is going
- eye gaze direction (Vector3): representing the direction of the user gaze
- eye gaze hit position (Vector3): position of the currently gazed at target
- eye gaze target name: ignore this field as we did not set this up properly
- left hand index position (Vector3) 
- left hand palm position (Vector3) 
- right hand index position (Vector3)
- right hand palm position (Vector3)
- head gaze origin: same as eye gaze origin
- head gaze direction: same as eye gaze direction
- head gaze hit position: same as eye gaze hit position
- head gaze target name: ignore this field
- 3d model position (Vector3): fox's position
- button 1 position (Vector3)
- button 2 position (Vector3): would be null in round 1
- button 3 position (Vector3): would be null in rounds 1 and 2
