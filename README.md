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
     git clone https://github.com/arjun-20/Fusion-AI-Chat-App.git
    cd multimodal-ai-chat

2. Create a Virtual Environment:
    python -m venv env
   
    env\Scripts\activate
   
    or
   conda create -n env python=3.10.*
   conda activate env
    
4. Upgrade pip: ``` pip install --upgrade pip ```

5. Install Requirements: ``` pip install -r requirements.txt ```

6. Setup local models: Download the models and place it inside the models directory.
      [Mistral](https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF)
      [Llava](https://huggingface.co/mys/ggml_llava-v1.5-7b/tree/main)
      [Whisper](https://huggingface.co/collections/openai/whisper-release-6501bba2cf999715fd953013)
```
multimodal_ai_chat-main/
├── models/
│   ├── mistral-7b-instruct-v0.1.Q5_K_M.gguf
│   ├── mistral-7b-instruct-v0.1.Q3_K_M.gguf
│   └── llava/
│       ├── ggml-model-q5_k.gguf
│       └── mmproj-model-f16.gguf
├── app.py
├── database_operations.py
├── config.yml
└── README.txt
```

7. Initialize the Database: ``` python3 database_operations.py ```
    
8. Run the Application: ``` streamlit run app.py ```


## Outputs
Chat Interactions:
![1](https://github.com/arjun-20/Fusion-AI-Chat-App/assets/73024645/ba5fedf7-382f-428d-9eaf-c49013ca710c)


PDF Interactions: 
![3](https://github.com/arjun-20/Fusion-AI-Chat-App/assets/73024645/e3e61eef-cb32-4dd7-ae94-8982de089c3e)


Image:
![2](https://github.com/arjun-20/Fusion-AI-Chat-App/assets/73024645/6b8653d6-c2dd-4c3f-ac6b-dd004c672c2d)


