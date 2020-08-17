# Python_Chatbot_Project
I have made a generative model based chatbot which doesn't respond based on the pre defined responses. It uses seq2seq neural networks nad has almost the same idea like the machine translation. The chatbot will be trained on training data set which contains patters, responses and intents. People can tweak the intents and update it further and use them for their own dataset.
First, we train the model using the command in the terminal:
```
python train_chatbot.py
```
Then we can run this from the command line .
```
python chatgui.py
```

We also need to have ```nltk,keras,tensroflow``` installed in order to run this chatbot
