# Jenkins MyPython App

### Description
Learning the basics of Jenkins with the help of flask library. Creating a simple hello world flask app and testing in in Jenkins.

### Git commands used:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.

### Steps:
1. Building the files required:
app.py: flask code, 
requirements.txt: contains required libraries, 
JenkinFile: contains commands to be run in Jenkins, 
test_app.py: code to test app.py file.
2. Create a new item in Jenkins with the desired name in Pipeline item type.
3. Select GitHub hook trigger for GITScm polling
4. Select Pipeline script from SCM in the pipeline section
5. Paste the github repository url that contains all teh required files 
6. Save the configurations
7. Build now & visualize the console output.

### Output:
![image](https://github.com/user-attachments/assets/5231a60c-52b0-4f98-af09-aeca7b1184a5)

