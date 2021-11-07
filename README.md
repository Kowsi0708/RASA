 # 1.	Introduction:
A chatbot is an application that can initiate and continue a conversation using auditory and/or textual methods as a human would do. A chatbot can be either a simple rule-based engine or an intelligent application leveraging Natural Language Understanding. Many organizations today have started using chatbots extensively. Chatbots are becoming famous as they are available 24*7, provide a consistent customer experience, can handle several customers at a time, are cost-effective and hence, results in a better overall customer experience.
 # 1.1	Uses
•	Customer support
•	Frequently Asked Questions
•	Addressing Grievances
•	Appointment Booking
•	Automation of routine tasks
•	Address a query

 # 2.	Prerequisites
The prerequisites for developing and understanding a chatbot using Microsoft Azure are:
•	Python installed
•	Microsoft Build tools with visual c++ 14.0 installed. Link: https://visualstudio.microsoft.com/downloads/

 # 3.	Introduction to RASA
Rasa is an open source machine learning framework for building contextual AI assistants and chatbots.
Rasa has two main modules:
•	NLU for understanding user messages 
•	Core for holding conversations and deciding what to do next 
 # 3.1	RASA Architecture:
 ![image](https://user-images.githubusercontent.com/91020536/140633310-17633bea-2f75-4581-8f97-d88d9dcd1175.png)


 # 4.	The problem statement
The goal here is to build a chatbot which can answer queries related to the COVID-19 disease.
 #4.1	Technical stack:
*	Python
*	Rasa X
 # 4.2	The application flow
![image](https://user-images.githubusercontent.com/91020536/140633372-e8090d76-dc28-4910-9a09-a5928b5a9839.png)
  # 5.	Implementation:
•	Create a new folder for your chatbot project.
•	Open that folder using Pycharm
•	Create a new environment for your chatbot project from pycharm or from anaconda prompt.
•	Run the command pip install rasa x for installing all the rasa dependencies
•	Run the command pip install spacy for installing spacy library.
•	Then enter the following commands:
	python -m spacy download en
	python -m spacy download en_core_web_md
	python -m spacy link en_core_web_md en

•	After all this command run successfully, enter the command rasa init and for all the subsequent actions choose Y (for training the model etc).
•	After all this, you can just enter the command ‘rasa train’ to train the model with new conversation elements.
•	After the training is completed, enter the command ‘rasa x’ to test your chatbot in the web UI. You’ll see :

![image](https://user-images.githubusercontent.com/91020536/140633514-53b0e05c-a777-4318-bd12-c26a170e828a.png)

•	Copy this URL in your web browser and you’ll see the web UI for your chatbot
