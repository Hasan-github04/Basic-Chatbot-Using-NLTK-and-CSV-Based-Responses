# Basic-Chatbot-Using-NLTK-and-CSV-Based-Responses
This chatbot is implemented using Python's NLTK library and pandas for dynamic, CSV-driven responses. It follows a rule-based approach using pre-defined patterns and responses stored in a CSV file.

How It Works:

1. Loading Responses – The chatbot loads conversational patterns and responses from a CSV file using pandas. The dataset consists of user input patterns mapped to corresponding replies.
2. Chatbot Initialization – The chatbot is built using NLTK’s Chat class, leveraging the loaded response pairs along with predefined reflections (e.g., handling pronoun swaps).
3. User Interaction – The chatbot continuously takes user input, processes it using pattern matching, and returns the appropriate response.
4. Exit Condition – The conversation runs in a loop until the user types "bye", at which point the chatbot terminates gracefully with a farewell message.
   
This implementation allows easy customization by modifying the responses.csv file, making it adaptable for different chatbot applications.
