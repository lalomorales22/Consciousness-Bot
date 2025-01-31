# Consciousness Explorer & Chat Bot

A Python-based desktop application that combines educational content about consciousness with an AI chatbot powered by Ollama.

## Features

- Multiple tabs with curated content about consciousness theory
- Interactive chatbot using Ollama's API
- Support for multiple LLM models
- Real-time streaming responses
- Clean, user-friendly interface

## Prerequisites

- Python 3.x
- Ollama server running locally
- Required Python packages:
  - tkinter
  - requests

## Installation

1. Install required packages:
```bash
pip install requests
```

2. Ensure Ollama is installed and running on your system (port 11434)

3. Clone the repository:
```bash
git clone https://github.com/lalomorales22/Consciousness-Bot.git
cd Consciousness-Bot
```

## Usage

Run the application:
```bash
python app.py
```

The application features:
- Summary tab - Overview of consciousness theories
- Blog Post tab - Detailed exploration of concepts
- 50 Posts tab - Quick insights and thoughts
- Analysis tab - Practical applications
- Conscious Bot tab - Interactive AI chat

## Available Models

- Granite3Moe_3b
- Qwen2_5_Coder_7b
- Granite3Dense
- Phi3_5
- SmallThinker
- Gemma
- And more...

## Configuration

The Ollama API endpoint is configured to `http://localhost:11434/api/generate` by default. Modify `OLLAMA_URL` in the code if needed.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
