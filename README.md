# Gemini-Powered-MultiPDF-Chatbot

![gemini](https://github.com/shaadclt/Gemini-LangChain-MultiPDF-Chatbot/assets/98437584/9c826ccf-6dca-40fb-86b6-ab77bb2c9e3f)

Gemini-Powered-MultiPDF-Chatbot is a Streamlit application that leverages Google Generative AI Gemini and LangChain for conversational question-answering based on PDF documents. This chatbot allows users to ask questions related to the content of uploaded PDF files.

## Features
- **Conversational Chatbot:** Utilizes Google Generative AI for conversational question-answering.
- **PDF Processing:** Extracts text from uploaded PDF files.
- **Vectorization:** Converts text chunks into embeddings for efficient similarity search.
- **User Interaction:** Users can ask questions related to the content of PDF files.

## Usage
1. Installation
Clone the repository:

```bash
git clone https://github.com/shaadclt/Gemini-Powered-MultiPDF-Chatbot.git
cd Gemini-Powered-MultiPDF-Chatbot
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Running the Application
```bash
streamlit run app.py
```

## Usage Instructions
   
1. Upload PDF files using the file uploader.
2. Ask questions related to the content of the PDF files in the text input box.
3. Click "Submit & Process" to extract text from the uploaded PDF files and process the user's question.
4. The chatbot will provide an answer based on the context of the uploaded PDF files.
   
## Dependencies
- Streamlit
- PyPDF2
- langchain
- Google Generative AI
- python-dotenv

## License
This project is licensed under the MIT License.
