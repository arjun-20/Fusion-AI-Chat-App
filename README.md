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
    ``` git clone https://github.com/arjun-20/Multimodal-AI-Chat-App.git
    cd multimodal-ai-chat ```

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

6. Initialize the Database:
   python3 database_operations.py
    
7. Run the Application:
    streamlit run app.py
    
