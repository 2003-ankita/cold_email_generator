## cold_email_generator
The Cold Email Generator is a powerful tool designed for service-based businesses looking to enhance their outreach efforts. By leveraging Groq, Langchain, and Streamlit, the tool simplifies the process of creating personalized cold emails tailored to specific job listings. Users can input the URL of a company’s careers page, and the tool automatically extracts job openings from the page. It then generates custom cold emails, enriched with portfolio links that are intelligently selected from a vector database, based on the specific skills and requirements of each job description.

## Set-up

### 1. Get the API Key
To get started, first obtain an API key from **Groq**: [Groq API Key](https://console.groq.com/keys). Once the API key is created, update the value of `GROQ_API_KEY` inside the `.env` file located at `app/.env`

## 2. Install Dependencies
To get started, first install the dependencies using:
   ```bash
   pip install -r requirements.txt
  
## 3. Running the App
To start the Streamlit app, use the following command:
   '''bash
   streamlit run app/main.py


