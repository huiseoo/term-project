# AI-TRAINER

### ABOUT 
There were two people in the group who exercised as a hobby, so I thought about working on a project based on exercise.

1. Project.py
   This code utilizes the open-source library called Mediapipe, developed and maintained by Google, along with OpenCV. It is designed to detect and track the pose of a user through a webcam, extracting the positions and angles of the joints.

2. Pose.py
   This code calculates the number of exercises based on the angles measured by the Pose.py module. It uses a detector object to find the pose and track the positions of joints. There are separate functions for measuring push-up and squat exercises.

## What we added
We added an empty list called exercise_records to store records for each exercise. We introduced a method called recordExercise to record the exercise name, timestamp, and detected joint positions. Additionally, we added a method named saveExerciseRecords to save the recorded exercise data to a CSV file.

Through these additions, users can track and record detailed information for each exercise session.



*We imported Mediapipe, but despite spending numerous hours during the exam period, we discovered that the Python version installed in the virtual environment was not compatible with the version of Mediapipe we installed. Consequently, after reinstalling the correct Python version in the virtual environment, persistent conflicts between the virtual environment and the installed Python version prevented us from making any progress. We attempted the same process on a different laptop, but we still couldn't find a solution. Please understand our efforts and be lenient in your evaluation. Thank you.*

## **Requirements: (with versions i tested on)**
python : 3.10.12
Mediapipe
opencv
numpy


Source: https://github.com/Yega-Noragami/AI-TRAINER
