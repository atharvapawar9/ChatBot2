<h1>Chat with Google Gemini-Pro!</h1>
<p>This project integrates a chatbot built using Streamlit and Google's Gemini-Pro model, allowing users to interact with an AI assistant directly from a web interface. <br>The code enables conversational AI features with a simple and user-friendly interface.</p>
<h2>Features</h2>
<p>
  <ul>
    <li><b>Streamlit Integration:</b> Provides a clean and interactive UI.</li>
    <li><b>Google Gemini-Pro Integration: </b>Uses Google's Gemini-Pro model for generating AI responses.</li>
    <li><b>Chat History: </b>Displays past interactions for context.</li>    
  </ul>
</p>
<h2>Prerequisites</h2>
<p>
  <ul>
    <li>Python 3.7+ </li>
    <li><b>Streamlit:</b> To install Streamlit, run: <br>
     ```bash
       
      streamlit run <your-app_name>.py
    ```
    
</li>
    <li><b>Google Gemini AI SDK:</b> Install the required SDK with:<br> '''pip install google-generativeai</li>
  </ul>
</p>
<h2>How to Use</h2>
<ol>
  <li>Clone the repository or copy the code into your local project.</li>
  <li>Set up your API key<br>  '''api_key = "YOUR_API_KEY"'''</li>
  <li>Run the app locally<br> '''streamlit run your_script.py'''</li>
  <li>Open the Streamlit app in your browser</li>
</ol>
<h2>Code Overview</h2>
<p>
  <ul>
    <li><b>Initialization:</b> The Google Gemini-Pro API is configured with your API key.</li>
    <li><b>Streamlit UI:</b> Chat history is displayed, and users can input their queries.</li>
    <li><b>AI Interaction:</b> User input is sent to Google Gemini-Pro, and responses are displayed in the chat interface.</li>
  </ul>
</p>
