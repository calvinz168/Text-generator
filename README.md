# Machine Learning Text-generator

A machine learning text generator built for Oakhacks using python on Jupyter Notebook, which works by slicing text into 'seeds', calculating the probability that a character follows another character, and generates text based off of this probability. 

# How it Works

1. User inputs a text to train and ‘seed’ the AI
2. The program slices up the text into 50 character lines - ‘seeds’
3. Using a Long-Short Term Memory(LSTM) neural network, the program assigns a probability to each character following another character within the text
4. The text is generated and printed to the console
5. Using the generated text, the model trains and fits itself to improve

# Applications

Education
- Able to replicate the specific writing style and format of Shakespeare and other renowned authors with particular writing styles
- AI is able to replicate any writing style with enough training, even in old english or other languages given enough text and time
- Automation to generate written exemplars, instructions, or write speeches

Predictive Text
- Based on the nature of how the program is designed, it is able to predict what you are going to say by training itself on your previous data, therefore applicable to mass consumers
- Very helpful to assisst the disabled, as well as those learning languages
