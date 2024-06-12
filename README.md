

# Chat with Multiple PDFs

This project is a Streamlit application that allows users to upload multiple PDF documents and interact with them through a conversational interface. The application leverages natural language processing to understand user queries and provide relevant responses based on the content of the uploaded PDFs.

## Features

- Upload multiple PDF documents.
- Extract text from uploaded PDFs.
- Split extracted text into manageable chunks.
- Generate embeddings for text chunks using OpenAI or HuggingFace embeddings.
- Store and retrieve text chunks using FAISS vector store.
- Engage in a conversational interface with the PDF content using OpenAI's Chat API.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SelahattinNazli/Chat_with_Multiple_PDFs.git
   cd Chat_with_Multiple_PDFs
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory of the project.
   - Add your OpenAI API key and HuggingFace API token to the `.env` file:
     ```
     OPENAI_API_KEY=your_openai_api_key
     HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token
     ```

## Usage

1. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

2. **Interact with the app:**
   - Upload PDF documents via the sidebar.
   - Ask questions about the content of the uploaded PDFs in the text input box.

## File Structure

- `app.py`: The main application script.
- `htmlTemplates.py`: Contains HTML templates for rendering chat messages.
- `.env`: Environment variables file (not included in the repository for security reasons).

## Example

1. **Upload PDFs:**
   - Use the sidebar to upload one or more PDF files.
   
2. **Ask a Question:**
   - Enter a question related to the content of the uploaded PDFs in the text input box.

3. **Get Responses:**
   - The application will process the PDFs and generate responses based on the content.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---




