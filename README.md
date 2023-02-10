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

This model consists of three hidden linear layers and one output layer. It uses nltk for natural language processing. This  model is trained on root words only for which we are using stemmer. It makes use of in-built python libraries to make code simpler. This model takes user query as voice input and coverts it into text which is then used to find the appropriate response and then outputed as voice reply to the user.

Note: If specific libraries which are used in the code are not installed in the system, they have to be pre-installed before running the code, else the code might throw some error.
