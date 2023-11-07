# FAQ_chatbot_iitb
I have implemented a chatbot that answers questions that people generally have about IITB, using the RASA Open Source framework.
After creating a virtual environment with python 3.6 and installing and setting up the basic RASA model on it, I started editing the training data in order to suit my purpose.
The bot is designed to answer questions a JEE aspirant might have about IITB. Examples:
1. How are the courses at IITB?
2. Is IITB better than IITD?
3. What is Mood Indigo?
   
I edited the domain.yaml,NLU.yaml,stories.yaml files in order to add addi- tional intents and responses corresponding to various questions about IITB.
The configuration used to train the model was the same as RASA’s default training configuration as we have just added onto the default RASA chatbot.
RASA already has a robust pipeline to train the intent classification and response generation features of the module and is more than sufficient for this purpose.
