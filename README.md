**DOCUMENTATION**

**1.TITLE:**

- Multi-User Contextual Conversational Chatbot with User-Specific Memory using SQLite database.

**2.DESCRIPTION:**

- This code implements a conversational chatbot that allows multiple users to interact with it. 
- The chatbot is designed to remember the context of each individual user's conversation, providing a personalized experience. 
- The code utilizes SQLite as a database to store user conversations and their respective histories.

**3.INSTALLATION:**

- Use the following command to install the required dependencies:         

“pip install openai langchain pypdf chromadb tiktoken”

**4.PREREQUISITES:**

- Python 3.x installed.
- Required libraries: sqlite3, langchain (with its dependencies), OpenAI API key.

**5.USAGE:**

- Clone this repository to your local machine.
- 2. Open the “app.py” script in your preferred Python environment.
- 3. Run the script to create the chatbot interface.

**6.FEATURES:**

- Supports multiple users interacting with the chatbot.
- Maintains individual conversation histories for each user.
- Utilizes SQLite for efficient storage and retrieval of user conversations.
- Employs LangChain components, including RetrievalQA, to generate bot responses.
- Allows users to exit the conversation.

**6. WORKING:**

- The script initializes a SQLite database to store user conversations and their histories.
- Users are prompted to enter their unique user ID.
- The chatbot engages with the user by responding to their input.
- The conversation history for each user is stored in the SQLite database, maintaining the context of the conversation.
- Users can exit the conversation by typing 'exit'.

**6. LICENSE:**

- This project is licensed under the MIT LICENSE.

**7. CONTACT INFORMATION:**

For any questions or feedback, please contact:

- Name- Niket Virendra Patil
- Email- pniket7@gmail.com






