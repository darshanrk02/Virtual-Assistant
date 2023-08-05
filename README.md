# Virtual-Assistant
Virtual Assistant built on Deep Neural Networks

This model uses the following main python libraries:
1. pyttsx3 : to convert text to speech
2. speech_recognition : to recognize voice and convert it into text
3. pytorch : used to create/add deep neural networks
4. numpy : to make calculations easier
5. nltk : for language processing purposes(tokenizing sentence, stemming words etc. )
6. wikipedia : to sumarrize wikipedia content of the asked query
7. pywhatkit : used to google search a query

DataSet : This model is trained on self made training data set called intents.json file. If any new features are required it can be added, but the format of the json file should remain same.

This model is designed with three hidden layers and one output layer. It uses a tool called NLTK to understand human language. The model is trained to focus on the basic forms of words using a process called stemming. It utilizes pre-existing tools available in Python to maintain a simple and easy code.

Here's how it works: When you talk to the model, it listens to your voice and turns it into written words. Then it figures out the best answer based on those words. Finally, it speaks out the answer in response to you.

Note: If specific libraries which are used in the code are not installed in the system, they have to be pre-installed before running the code, else the code might throw some error.
