# Consumption Forecasting

### Description
A time series forecasting model which uses Mean Squared Error (MSE) as metric for predition

### Git and other commands used in command prompt:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.

Docker commands:
1. `docker build -t <folder_name> .`
2. `docker run <folder_name>`

Selenium:
`pip install selenium`

### Steps: 
1. Create the required files such as the dataset csv file, training model python file, requirements.txt file and Dockerfile
2. Create a new item under Freestyle Project in Jenkins
3. Select Git in Source Code Management and paste your repository url in the given space
4. Add Execute Windows Batch Command step in Build Steps
5. Save the configurations
6. Build now and visualize the console output
7. Now open the command prompt with the path of the folder containing the requied files
8. Run the docker commands mentioned above in the command prompt
9. Visualize the result in the command prompt and in the Docker desktop app
10. Install selenium from the command prompt
11. Execute the selenium commands

### Output:
![image](https://github.com/user-attachments/assets/cc25e1a2-6530-4d6e-8b8c-bf6295aa8a40)
![image](https://github.com/user-attachments/assets/74b64d65-d312-4626-b5be-433bbd49e166)


