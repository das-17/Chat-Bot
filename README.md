# Chat-Bot
A simple medical-aid chat-bot created using Python. 
The following are the machine-learning libraries used:-
- NumPy
- NLTK

The following are the framworks utilized:-
- Keras
- TensorFlow

The chat-bot directs you to the following sub-modules based on the user interaction:-
- Medical Records based on patient name/id
- Test Results based on patient name/id
- Nearby pharmacy details
- Nearby Hospital details

Future work:Functionality of the sub-modules to retreive data based on some sample data.

To run the chatbot we need to run two commands, the first to train the chatbot with the intents.json to generate a model and the second to 
run the GUI.
```
python train_chatbot.py
python chatgui.py
```
Files needed to locally run it are:
- intents.json
- train_chatbot.py
- chatgui.py

