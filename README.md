# ChatMate

ChatMate is an AI-driven chatbot that uses machine learning and natural language processing (NLP) to understand user intents and respond intelligently. Built with TensorFlow and Python, ChatMate classifies user input into specific intent categories and generates meaningful, customizable responses in real-time.

Key Features


• Intent Classification: Powered by a deep learning model, ChatMate accurately identifies user intentions, leveraging a Sequential neural network for multi-class text classification.


• Customizable Conversations: The response patterns are easily adjustable in a JSON file, making ChatMate adaptable to various applications.


• User-Friendly Interface: Interact with ChatMate directly from the console in a conversational, interactive format.


• Persisted Model Components: ChatMate’s trained model, tokenizer, and label encoder are saved for efficient deployment and continuous use.


How It Works


• Data Preparation: Using a JSON dataset, ChatMate tokenizes and encodes text patterns to classify inputs accurately.


• Model Training: With an embedding layer, global average pooling, and dense layers, the model is trained for robust intent recognition using sparse_categorical_crossentropy loss.
• Dynamic Response Generation: ChatMate matches each recognized intent with a relevant, randomized response from a predefined list, delivering varied and natural replies.
• Deployment-Ready: The trained model, tokenizer, and label encoder are loaded at runtime, making the chatbot lightweight and optimized for deployment.
Tech Stack
• Language: Python
• ML Framework: TensorFlow/Keras
• NLP: Tokenizer, LabelEncoder
• Data Format: JSON for intent and response configuration
Getting Started
• Clone this repository and navigate to the project directory.
• Install dependencies listed in requirements.txt.
• Start the chat by running the main file, and enjoy your interaction with ChatMate!
