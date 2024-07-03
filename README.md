# Multimodal-AI-Chat-App
A real-time local AI Chat application to seamlessly handle PDFs, images, and audio interactions.
## Features

- Quantized Model Integration: Optimized models for better performance on regular consumer hardware.
- Audio Chat: Utilizing Whisper AI for robust transcription capabilities.
- Image Chat: Employing LLaVA for advanced image understanding.
- PDF Chat: Integrating Chroma DB for efficient PDF interactions.
- Text Chat: Using the Mistral 7B model for engaging and intelligent text conversations.

## Getting Started

### Prerequisites

- Python 3.10.12
- pip (Python package installer)

### Installation

1. Clone the Repository:
    git clone [https://github.com/yourusername/local-multimodal-ai-chat.git](https://github.com/arjun-20/Multimodal-AI-Chat-App.git)
    cd multimodal-ai-chat

    
2. Create a Virtual Environment:
    python -m venv env
    env\Scripts\activate
    or
   conda create -n env python=3.10.*
   conda activate env
    

4. Upgrade pip:
    pip install --upgrade pip
    

5. Install Requirements:
    pip install -r requirements.txt
    

    Main Dependencies:
    - chromadb==0.4.23
    - ctransformers==0.2.27
    - InstructorEmbedding==1.0.1
    - langchain==0.1.9
    - langchain-community==0.0.22
    - llama-cpp-python==0.2.20
    - librosa==0.10.1
    - pypdfium2==4.27.0
    - pyyaml==6.0.1
    - sentence-transformers==2.3.1
    - streamlit==1.31.1
    - streamlit-mic-recorder==0.0.4
    - transformers==4.38.1

6. Initialize the Database:
   python3 database_operations.py
    

7. Run the Application:
    streamlit run app.py
    
