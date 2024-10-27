# Credit Risk Management

### A freestyle project in Jenkins and a regression type prediction model using Random FOrest CLassifier algorithm that uses accuracy_score as the metric prediction.

### Github commands used:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.
   
Docker:
1. `docker build -t <folder_name>`
2. `docker run <folder_name`
   
### Steps:
1. Building the files required: app.py: flask code,
requirements.txt: contains required libraries,
credit_risk_dataset.csv: The required dataset for this model, 
train_model.py: code to test the file,
Dockerfile: contains commands to be run in docker
2. Create a new item under Freestyle Project type in Jenkins.
3. Select Git in Source Code Management and paste your repository url in the given space
4. Add Execute windows batch command in Build Steps
5. Build now and visualize console output
6. Open command prompt with the directory of the folder with the required file
7. Run the docker commands mentioned above
8. Visualize the output in both command prompt and Docker desktop app

### Output:
![image](https://github.com/user-attachments/assets/26f9efc3-38e0-4cf7-ad95-00a8d2e5e3ab)
![image](https://github.com/user-attachments/assets/bba9d315-54fc-4c21-9897-50402a43e903)


