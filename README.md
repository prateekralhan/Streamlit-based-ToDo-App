# Streamlit based ToDo App 📝[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)

A simple Streamlit based To-Do webapp to keep a track of your daily tasks :wink:.

## Live webapp can be found [here](https://streamlit-todo-app.herokuapp.com/).

### Create Tasks ✅
![create_task](https://user-images.githubusercontent.com/29462447/155017556-1d10a946-60f5-4e25-a6a0-45184952e701.gif)

### Update Tasks 📝
![update_task](https://user-images.githubusercontent.com/29462447/155017585-2650a9ec-d5f9-4d62-a3a4-547925cecb10.gif)

### View All Tasks' Status 
![video_status_check](https://user-images.githubusercontent.com/29462447/155017600-d4f41dac-de93-451f-941b-4ac24c537c59.gif)

### Delete Task ❌
![delete_task](https://user-images.githubusercontent.com/29462447/155017611-f5d7ea58-df37-42fb-b746-fed931f79abf.gif)

## Installation:
* Simply run the command ***pip install -r requirements.txt*** to install the dependencies.

## Usage:
1. Clone this repository and install the dependencies as mentioned above.
2. Simply run the command: ***streamlit run app.py***
3. Navigate to http://localhost:8501 in your web-browser.


![1](https://user-images.githubusercontent.com/29462447/154963977-a9d281a0-2707-4956-8898-c9e16366e621.png)


### Running the Dockerized App
1. Ensure you have Docker Installed and Setup in your OS (Windows/Mac/Linux). For detailed Instructions, please refer [this.](https://docs.docker.com/engine/install/)
2. Navigate to the folder where you have cloned this repository ( where the ***Dockerfile*** is present ).
3. Build the Docker Image (don't forget the dot!! :smile: ): 
```
docker build -f Dockerfile -t app:latest .
```
4. Run the docker:
```
docker run -p 8501:8501 app:latest
```

This will launch the dockerized app. Navigate to ***http://localhost:8501/*** in your browser to have a look at your application. You can check the status of your all available running dockers by:
```
docker ps
```
