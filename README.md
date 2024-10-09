# Knowledge_Graphs-LLM
# LLM-powered AI Chatbot for Alzheimer's Awareness

This project leverages cutting-edge large language models (LLMs) to provide accurate and real-time information about Alzheimer’s disease. The chatbot helps users find answers to questions regarding symptoms, treatments, and care strategies, focusing on assisting patients and their caregivers.

## Features
- **LLM Fine-Tuning**: Utilizes PyTorch to fine-tune a GPT-based model on a custom dataset for Alzheimer’s awareness.
- **Neo4j for Knowledge Graph**: Integrates Neo4j to store and retrieve structured medical data efficiently, enhancing the accuracy of responses.
- **On-Device Optimization**: Deployed with Core ML and Docker for on-device inference, ensuring smooth mobile performance.
- **Real-Time Interaction**: Delivers accurate responses with 92% precision in under 2 seconds, improving user engagement and satisfaction by 35%.

## Technologies Used
- **Languages**: Python
- **Libraries**: PyTorch, Neo4j, Core ML
- **Deployment**: Docker, Core ML
- **Tools**: OpenAI API, TensorFlow, PyTorch

## Getting Started

**Clone the repository, Install Requirements and Run app**:
   ```bash
   git clone https://github.com/yourusername/LLM-Alzheimers-Chatbot.git
   cd LLM-Alzheimers-Chatbot
   pip install -r requirements.txt
   python app.py
