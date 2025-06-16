# MultiLanguage-coding-Assistant-using-CodeLlama
<div align="center">
  <h1>🤖 Coder Katoch</h1>
  <p><i>Your personal AI coding companion powered by Ollama</i></p>
  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
  ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=llama&logoColor=white)
  
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/main/icons/folder-python.svg" width="100" />
</div>

---

## ✨ Features

- 🚀 **Instant Code Assistance** - Get programming help in seconds
- 💬 **Conversation Memory** - Maintains context for better responses
- 🔌 **Local Execution** - Runs completely on your machine for privacy
- 🎨 **Clean UI** - Simple yet powerful Gradio interface

## 📋 Prerequisites

- Python 3.x
- Ollama installed and running locally
- The custom "coder_katoch" model

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/coder-katoch.git
   cd coder-katoch
   ```

2. **Install dependencies**
   ```bash
   pip install gradio requests
   ```

3. **Create the custom Ollama model**
   ```bash
   ollama create coder_katoch -f modelfile
   ```

## 🚀 Usage

1. **Start the application**
   ```bash
   python app.py
   ```

2. **Open your browser**
   Navigate to http://localhost:7860

3. **Start coding!**
   Type your coding questions and get expert assistance

## 🧠 How It Works

Coder Katoch connects to a locally running Ollama instance to leverage the power of CodeLlama. The application:

- Sends your queries to the Ollama API
- Maintains conversation history for context
- Returns formatted responses through a clean Gradio interface

## 📝 Model Details

The custom "coder_katoch" model is built on CodeLlama with:
- Temperature setting of 1 for creative responses
- Custom system prompt for coding assistance
- Optimized for programming knowledge and explanations




<div align="center">
  <p>Created with ❤️ by Aryan Katoch</p>
</div>
