# chronic-disease-monitoring-ai-agent-
Monitors chronic diseases like diabetes, hypertension, and heart conditions.  Uses wearable data, medical records, and user input.  Provides early alerts, personalized suggestions, and treatment reminders.
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/df7206ed-2dd2-4d53-a576-9c42551658a9" />

# Problem Statement
Chronic illnesses require continuous monitoring and timely interventions. Traditional systems are reactive and depend heavily on manual follow-ups. There is a need for a proactive AI-driven system that can help patients manage their conditions with timely reminders, predictions, and lifestyle guidance.
# Proposed Solution
1. We propose ChronicCare AI, an intelligent chatbot agent that:
2. Monitors vital signs and health inputs.
3. Detects abnormal health patterns.
4. Alerts users and caregivers.
5. Suggests treatments, exercises, or doctor visits.
6. Encourages compliance with medical instructions.
# Technologies Used
1. Python
2. Jupyter Notebook
3. HTML, CSS (for deployment dashboard)
4. JSON (intent training data)
# IBM Cloud Services Used
1. Watsonx Assistant – AI chatbot creation
2. Watsonx.ai Studio – Notebook development and model testing
3. Cloud Object Storage – Store structured/unstructured data
4. Watson Discovery (optional) – Extract insights from documents
5. IBM Cloud Functions – For webhook and event-driven automation
# End Users
Patients with chronic diseases
Family members/caregivers
Healthcare providers/clinics
# Key Features
1. AI assistant for health monitoring
2. Personalized recommendations
3. Daily reminders (medicines, exercise, checkups)
4. Interactive chatbot (Watsonx Assistant)
5. Secure handling of medical data
# How It Works
User interacts with ChronicCare AI chatbot via web/app.
System fetches relevant health data from wearables or manual input.
AI model detects anomalies or missed patterns.
Personalized response or alert is generated.
User receives health suggestions or reminders
# Screenshots
Resource List...
<img width="1883" height="907" alt="Screenshot 2025-08-02 225118" src="https://github.com/user-attachments/assets/18d39445-23d8-4203-a71c-91f66b0b55a9" />

Setting Up...
<img width="898" height="774" alt="Screenshot 2025-08-02 125157" src="https://github.com/user-attachments/assets/3c314dba-9895-4fc2-824a-421e957fafd9" />

Agent Instructions...
<img width="819" height="825" alt="Screenshot 2025-08-02 133648" src="https://github.com/user-attachments/assets/c50d4f67-fe1e-4383-af47-a08cd86142cc" />

Quick Start Questions...
<img width="935" height="828" alt="Screenshot 2025-08-02 133801" src="https://github.com/user-attachments/assets/1f47f2cc-de10-4e80-b973-115415bb47f1" />

Tools used & Testing...
<img width="921" height="910" alt="Screenshot 2025-08-02 161051" src="https://github.com/user-attachments/assets/9975952e-9375-47a6-97b3-56aff4a8bfa9" />

Deployment & Preview...
<img width="1920" height="1080" alt="deployment" src="https://github.com/user-attachments/assets/ecb80481-6d48-4451-90e4-431e87777221" />
<img width="925" height="759" alt="Screenshot 2025-08-02 134253" src="https://github.com/user-attachments/assets/e2ed8104-e5b4-4f75-a867-4f0b05189637" />

<img width="917" height="833" alt="Screenshot 2025-08-02 134505" src="https://github.com/user-attachments/assets/cbdca3fb-f541-469c-93e0-dea62846c1eb" />

# How to Run or Deploy
1. Log in to IBM Cloud Lite: https://cloud.ibm.com
2. Launch Watsonx.ai Studio
3. Create a new AI Agent
4. Upload financial PDFs to a Vector Index
5. Choose Tools for web search (Google,Wikipedia,DuckDuckGo etc..)
6. Configure agent instructions and topics (restricting AI from answering off-topic questions politely)
7. Test in the preview panel
8. Deploy via web snippet, Streamlit, or custom web UI
# Future Scope
1. Integration with smartwatches (Fitbit, Apple Watch)
2. NLP-based conversation memory
3. Support for multiple languages
4. EMR/EHR system connection
5. Health risk prediction via ML models

