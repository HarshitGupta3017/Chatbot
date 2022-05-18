# Covid Chatbot Using Rasa Framework

Corona virus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus. Most people infected with the virus will experience mild to moderate respiratory illness and recover without requiring special treatment. However, some will become seriously ill and require medical attention. With the recent outbreak of the pandemic, there have been mass panic among the communities. A chatbot is an artificial intelligence (AI) software that can simulate a conversation (or a chat) with a user in natural language through messaging applications, websites, mobile apps or through the telephone. A Chatbot can help us automate the regular responses to general queries, eliminating the need of human intervention. Although a human help can be provided when required.  

## Pre-Requisites

<li>Create a virtual environment </li>

    python -m venv chatbotEnv
    
<li>Activate the environment </li>

    chatbotEnv\Scripts\activate
    
<li>Run the following commands</li>

    python -m pip install --upgrade pip
    pip3 install rasa
    pip3 install rasa[spacy]
    python -m spacy download en
    pip install sklearn_crfsuite
    
<li>Now use following command to run the rasa in shell</li>

    rasa shell

<p>You can now use rasa chatbot.</p>
