# Assignment 3: English to Hinglish Translation
## Challenges faced
- Encountered RateLimitError while integrating the ChatGPT API into my code from the following links:
- Link1: https://platform.openai.com/docs/introduction/overview
- Link2: https://platform.openai.com/account/api-keys
- RateLimitError: The RateLimitError I encountered indicates that I've exceeded the rate limits of my OpenAI API plan. This means I've made too many requests in a short period of time according to my current plan's limits.
  
- Explored Python Graphical User Interface approach
  
- Encountered TclError while importing the Tkinter library

## Workflow
- First I prepared the environment for creating interactive widgets and performing language translation within my notebook. It sets up the necessary libraries to display interactive elements and perform translations but doesn't contain any specific functionality on its own.

- Then it takes English text as input, splits it into words, and attempts to translate each English word into Hinglish (a mix of Hindi and English). If a word cannot be translated, it keeps the original English word in the output. The translated and original words are then combined into a single Hinglish sentence and returned as the result.

- Then a function is designed to respond to an event (possibly a button click) triggered in a GUI. It takes the text entered by the user in an input widget, translates it to Hinglish using the translate_to_hinglish function, and displays the translated text in an output widget. This allows users to enter text in one language (presumably English) and see the translation in Hinglish in the GUI.

- Then I set up an input widget that can be used in a GUI. When displayed, it will show the text "Enter English Text" inside the input field, and it will have a label "Input Text:" associated with it, indicating that users should enter English text into this widget. This widget can be integrated into a GUI, allowing users to input text for translation or other purposes.

- Then I set up an output widget that can be used in a GUI. When displayed, it will initially be empty and labeled "Hinglish Output:". Users won't be able to edit the text in this widget; it's designed to show output or results, such as the translation of English text to Hinglish. This widget can be integrated into a GUI to display the translated text or other informational content to the user.

- Then I set up a "Translate" button widget in a GUI. When users click this button, it triggers the translate_text function to perform the translation based on the text entered in the input widget and display the result in the output widget. This button provides an interactive way for users to initiate the translation process.

- Finally, I completed the setup of the graphical user interface (GUI) by displaying the input field, the "Translate" button, and the output text area. Users can enter English text, click the "Translate" button, and see the translation result in the output area. This creates a user-friendly interface for the translation process.

## Screenshots
![Screenshot (123)](https://github.com/SIDDHARTH107/Hinglish/assets/103374957/43b6ea17-59cb-40fb-992d-90970532fe7b)

![Screenshot (124)](https://github.com/SIDDHARTH107/Hinglish/assets/103374957/783bb841-d638-442d-a531-234195de9cbf)

![Screenshot (125)](https://github.com/SIDDHARTH107/Hinglish/assets/103374957/6915e5c4-f5da-4e44-bf91-ca3b27436a15)

![Screenshot (126)](https://github.com/SIDDHARTH107/Hinglish/assets/103374957/ea1fc334-83b6-4b80-80ee-76463d2ce39c)
