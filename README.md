# AI-HealthCare-Chatbot-System_Cerebras

## Project Overview
The **AI Healthcare Chatbot Website for Medical Queries** is a project designed to enhance healthcare accessibility by providing users with an AI-driven chatbot for real-time medical consultations. The chatbot leverages advanced NLP and machine learning models to respond to health-related queries, perform symptom assessments, and offer medical guidance. Users can upload PDFs and DOCX files for personalized consultations. The integration of pre-trained ChatGPT models with Pinecone ensures quick, contextually relevant responses. The Geoapify API provides location-based services to help users find nearby hospitals.
Integrating Cerebras Inference into AI Healthcare Chatbot can significantly enhance performance, with models like Llama 3.1 70B achieving up to 2,100 tokens per second—16 times faster than leading GPU solutions. This speed advantage is crucial in time-sensitive medical scenarios, enabling more rapid consultations. However, it's essential to ensure that the chatbot complies with HIPAA regulations to protect patient privacy and data security. 

## Key Features
- **Real-time Medical Consultations**: AI-driven responses to user health queries.
- **Document Upload**: PDF and DOCX support for personalized guidance.
- **Fast Data Retrieval**: Powered by Pinecone for efficient data indexing and retrieval.
- **Location Services**: Integrated Geoapify API for finding nearby hospitals.
- **Responsive Frontend**: Built using Flask and customizable HTML templates.
- **Scalable and 24/7 Support**: Ensures constant availability and reliable healthcare assistance.

## Technologies Used
- **Programming Languages**: Python
- **Frameworks**: Flask, LangChain
- **NLP Models**: Pre-trained ChatGPT (GPT-3.5)
- **Vector Database**: Pinecone
- **File Processing**: PyPDF2, python-docx
- **Frontend**: HTML/CSS
- **Location API**: Geoapify API
- **Development Environment**: Google Colab
- **Tunneling Service**: Ngrok

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ai-healthcare-chatbot.git
   cd ai-healthcare-chatbot
## Install dependencies: Run the following commands in Google Colab:


!pip install langchain langchain_community langchain_pinecone
!pip install langchain_openai
!pip install python-docx pypdf PyPDF2
!pip install sentence_transformers
!pip install flask pyngrok

## Set up API keys: Add your API keys in the code:

os.environ["PINECONE_API_KEY"] = "YOUR_PINECONE_API_KEY"
os.environ["OPENAI_API_KEY"] = "YOUR_CHATGPT_API_KEY"
PLACES_API_KEY = "YOUR_GEOAPIFY_API_KEY"

## Run the code: Execute the Python script in Google Colab. A local server link using Ngrok will be generated for accessing the chatbot.

## Access the Flask app: Copy and paste the Ngrok URL in your browser to interact with the AI healthcare chatbot.

## Future Enhancements
Multi-language Support: Expand the chatbot for multi-language capabilities.
Additional File Format Support: Add support for more document types (e.g., images with OCR).
Enhanced Data Sources: Integrate certified healthcare databases for more robust responses.
User Authentication: Secure login and user management features.
Appointment Scheduling: Implement functionality to book medical appointments.
Analytics Dashboard: Real-time user interaction and chatbot performance metrics.
API Keys Required
Pinecone
ChatGPT (OpenAI)
Geoapify
Ngrok Authtoken

## Cerebras Vs Chatgpt
<img width="863" alt="image" src="https://github.com/user-attachments/assets/d72fc5b4-848c-41f8-9a51-17cde1288fad" />

##Cerebras Hardware Capacity
<img width="1157" alt="image" src="https://github.com/user-attachments/assets/ea93a58a-c890-4fee-8683-8231f92d6cca" />
<img width="1110" alt="image" src="https://github.com/user-attachments/assets/77cdb81b-1b33-403a-af8a-e506c5726be2" />



## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please submit a pull request for any enhancements or bug fixes.
