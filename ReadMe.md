This python application is a Context-Based answering study assistant that uses Google Gemini pro language model to generate answers based on the context provided. 
Using PDF files uploaded by the user.

Follow the commands below to run the application:

1. **Create a virtual environment 🌍**:
    ```bash
    python -m venv <your-environment-name>
    ```
2. **Activate the virtual environment ✅**:
    - On Windows:
      ```bash
      .\<your-environment-name>\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source <your-environment-name>/bin/activate
      ```
3. **Install the required packages 📦📦**:
    - All the libraries requried to run the application:
        1. streamlit
        2. google-generativeai
        3. python-dotenv
        4. langchain
        5. PyPDF2
        6. faiss-cpu
        7. langchain_google_genai
    or just run the following command to install all the packages:
    ```bash
    pip install -r requirements.txt
    ```
4. **Configure the environment variables 🔤**:
    - Add the following environment variables to the `.env` file:
      ```bash
      GOOGLE_API_KEY=<your-google-api-key>
      ```
5. **Run the application ⚡**:
    ```bash
    streamlit run App.py
    ```
    your application should now be running on http://localhost:8501

⚠️ If at all the API key is not working, please do visit : 'https://aistudio.google.com/app/apikey'
and fetch for an API key and replace the key with already existing key in '.env' file 
