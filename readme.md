* Install Anaconda, VS Code, python 3.7

* after installing anaconda open anaconda prompt and move to the directory where the chatbot-master folder is present.

* commands :
1. **conda create --name rasa_dev python=3.7** (To Create a conda environment with python 3.7) _Create only if required_
2. **conda activate rasa_dev** (Activating the created environment) _can also use any existing environment_
2. **pip install -r requirements.txt** (Install all the requirements for the project) _Go to your desired environment and run the command_
3. **rasa train** (calculate time taken to train)
4. **rasa shell** (cmd line interface to interact with chatbot)
5. **rasa run --enable-api --cors "*" --debug** (To expose rasa api endpoint)
6. **rasa run actions** (To start Rasa Action Server api endpoints)
7. **python -m http.server 8000** (Start front end server)