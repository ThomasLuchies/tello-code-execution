# Executing code on the Tello drone
This repository will contain the files for the students that are following the [NHL-Stenden-Python-course-programming](https://github.com/MarkBenjamins/NHL-Stenden-Python-course-programming-exercises). It also contains a manual how you can execute your code on the drone and what the system is doing with the student’s code.

## :family_man_woman_girl_boy:Assemble the groups

Before you can work with the drone, you have to assemble your group and get permission:

- Form a group with around 4 to 5 other students.

- Ask the corresponding teacher for permission to receive a groups number.

- Receive the rights to access the GitHub page where you can push code to the drone.

  

## :gear:Setup your file

Each group gets one file to execute code on the drone. In order to acquire the group file, follow the instructions below:

1. Clone this repository.

2. Create a new Python file called group + your specific group number. (for example group1.py)

   *DISCLAIMER: Make sure your file name is unique within the entire repository.*

3. Commit your changes and push the file to the repository.


Now your code is ready to control the Tello drone, it will be executed within ? minutes.

## :man_technologist:Code execution 

The pushed code will be executed automatically. Every ? minutes the system will scan the repository for changed files. The system will then detect those changed files and place them in the system queue. The system queue is continuously executed through the Jenkins pipeline. The file in front of the system queue will be run and the code will be executed onto the drone.

*DISCLAIMER: If your code is not executed, please contact the teacher.*
