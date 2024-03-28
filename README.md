# Chat With Multiple PDFs
The Multiple PDFS Chat App is a Chatbot that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents.


## How does it works?
![Alt Text](https://miro.medium.com/v2/resize:fit:923/1*CJzoMxqFrxrDv2UpZt23ZQ.png)

The application follows these steps to provide responses to the user  questions:

--> PDF Loading: The app reads multiple PDF documents and extracts their text content.

--> Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

--> Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

--> Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

--> Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.



## Installation and Dependencies
To install the  Chatbot, follow these steps:

--> Clone the repository to your local machine.

--> Install the required dependencies by running the following    command:
    
    pip install -r requirements.txt

--> Obtain an API key from OpenAI and API tomen key fron Hugging Face and add it to the .env file in the project directory.

OPENAI_API_KEY=your_secrit_api_key
HUGGINGFACEHUB_API_TOKEN=your_secrit_api_token



## How to run it?
To use the Chatbot, follow these steps:

--> Ensure that you have installed the required dependencies and added the OpenAI and Hugging Face API key to the .env file.

--> Run the main.py file using the Streamlit CLI. Execute the following command:

    streamlit run main.py

--> The application will launch in your default web browser, displaying the user interface.

--> Load multiple PDF documents into the app and ask questions in natural language.


## License

[MIT](https://choosealicense.com/licenses/mit/)

