# Conversational Agent using RNN
This repo contains the work done as part of the B.Tech project. We implemented a conversational agent which is trained on a dialog corpus. It is capable of having small natural language conversations with the user. It is based on a generative model and hence does not require predefined responses for having a conversation.
## Setup
1. Install anaconda from the installer
2. Open command prompt and run "pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.1.0-cp35-cp35m-win_amd64.whl" command.
3. Run "conda install nltk" command
4. Open the python console by typing "python" in the command prompt
5. In the python console run the following code
	* import nltk
	* nltk.download('punkt')
6. Exit the python console by running "exit()" command

## Running the program
1. Open command prompt and move to chatbot directory
2. Run "python main.py" to train a new model or "python main.py --modelTag pretrainedv2 --test interactive" to run the already trained chatbot
