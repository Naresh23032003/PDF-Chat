# PDF Chat

This Streamlit web application allows users to interactively query information from uploaded PDF files. It incorporates a conversational AI model to answer questions based on the content of the provided PDF documents. Users can upload one or multiple PDF files, ask questions related to the content, and receive answers generated by the AI model.

## Features
- Upload PDF files
- Ask questions related to the uploaded PDF content
- Receive AI-generated answers based on the context of the PDF documents
- Configurable interface through the `.streamlit/config.toml` file

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Set up your Google Generative AI API key in the `config.py` file.
4. Run the application using `streamlit run app.py`.
5. Upload PDF files using the file uploader.
6. Type your question in the text input field.
7. Click on "Submit & Process" to process the uploaded PDFs and get the AI-generated answer.

## Configuration
You can configure the interface of the Streamlit app by modifying the `config.toml` file located in the `.streamlit` folder. Customize the interface settings according to your preferences.
