# English-helper
A discord bot that can help you with your English vocabulary. 
The project is written in Python. 
### Feature
#### This project allows you to memorize the vocabulary, and learn how to use them in real-world scenarios.   
### How it works
This program utilizes Google's Gemini model API to generate sentences based on a randomly selected word from a predefined list. Here's how it works:

1. Random Word Selection: The program selects a word at random from a specified list.

2. API Processing: The selected word is sent to Google's Gemini model API for sentence generation.

3. Sentence Formation: Gemini constructs a sentence using the chosen word.

4. Character Marking: The program identifies the chosen word within the generated sentence and marks its letters with underscores (_), except for the first and last letters which remain unchanged.
### How to use it
Here's how it operates:

1. Activation and Input:
Activate the bot in your Discord channel.
Input a command structured as "exam " followed by a number from 1 to 6 to specify the level of vocabulary desired.     
    Example: ```exam 5```
2. Sentence Generation:
The bot generates a sentence containing a specific word marked with underscores (_).
Answer Submission:

3. Respond with "ans" followed by your answer to the marked word.  
    Example: ```ans apple```
4. Feedback Mechanism:
If correct, you'll receive confirmation of your correct answer.
If incorrect, the bot provides:
    - The correct word.
    - Its part of speech.
    - Its Chinese definition to aid in learning.

### Read before use
Remember to paste your own discord and Gemini token into the code.

### About the vocabulary list
The vocabulary level is based on the vocabulary list by the Ministry of Education of the Republic of China.
You may need to find the vocabulary list yourself.

### Problems
Sometimes Gemini would produce a bulk of response instead of a sentence, I don't know how to fix it :(.  Perhaps the prompt isn't correct.
