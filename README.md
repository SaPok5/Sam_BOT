# Sam_BOT

<div align="center">

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Flask](https://img.shields.io/badge/flask-v2.0+-green.svg)
![LangChain](https://img.shields.io/badge/langchain-latest-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

**A sophisticated AI-powered document assistant built with Google's Gemini API and LangChain**

[Features](#features) • [Installation](#installation) • [Usage](#usage) • [Documentation](#documentation) • [Contributing](#contributing)

</div>

## 🌟 Overview

Sam_BOT is an advanced document assistant that helps users extract information, analyze content, and interact with documents through natural language. Powered by Google's Gemini language model and built with a modern tech stack, Sam_BOT provides a seamless interface for document processing and information retrieval.



## ✨ Features

- **📄 Intelligent Document Processing**
  - Process PDFs, Word documents, text files, CSVs, and Markdown
  - Extract key information using semantic understanding
  - Summarize document content with structured formatting

- **🤖 Advanced AI Capabilities**
  - Powered by Google's Generative AI (Gemini)
  - Context-aware conversation handling
  - Professional, structured responses with Markdown support

- **💼 Business-Ready Features**
  - Appointment scheduling system
  - Session persistence
  - Multi-document management

- **🔒 Security & Privacy**
  - Content filtering and safety settings
  - Secure document handling
  - API key protection

## 🚀 Installation

### Prerequisites

- Python 3.8 or higher
- Google Cloud Platform account with Gemini API access
- Virtual environment (recommended)

### Quick Start

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/sam_bot.git
cd sam_bot
```

2. **Set up a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Configure environment:**

```bash
cp .env.example .env
# Edit .env with your Gemini API key and other settings
```

5. **Run the application:**

```bash
python main.py
```

The application will be available at `http://localhost:5000`.

## 💻 Usage

### Document Upload

1. Navigate to the "Upload Documents" tab
2. Drag and drop files or use the file browser
3. Supported formats: PDF, DOCX, TXT, CSV, MD

### Querying Documents

1. Switch to the "Chat" tab
2. Ask questions about your documents
3. Use natural language for queries like:
   - "Summarize this document"
   - "What are the key points in section 3?"
   - "Extract the financial data from the report"

### Appointment Scheduling

1. Ask Sam_BOT to schedule an appointment
2. Provide requested details (date, time, purpose)
3. View and manage appointments in the Appointments tab

## 📚 Documentation

Comprehensive documentation is available in the [DOCUMENTATION.md](DOCUMENTATION.md) file, covering:

- Detailed architecture
- API references
- Core components
- Deployment options
- Troubleshooting
- Security considerations

## 🔧 Configuration

The system can be configured through environment variables:

```
GEMINI_API_KEY=your_api_key_here
MODEL_NAME=gemini-pro
TEMPERATURE=0.7
CHUNK_SIZE=1000
CHUNK_OVERLAP=100
EMBEDDING_MODEL=sentence-transformers/all-MiniLM-L6-v2
```

## 🤝 Contributing

Contributions are welcome! Please check out our [contribution guidelines](CONTRIBUTING.md) first.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



## 🙏 Acknowledgments

- Google Generative AI Team
- LangChain Community
- All contributors to this project

## 📞 Support

For support, please:
1. Check the [documentation](DOCUMENTATION.md)
2. Open an issue
3. Contact the maintainers at support@example.com

---

<div align="center">
  <sub>Built with ❤️ by the SaPok</sub>
</div>

