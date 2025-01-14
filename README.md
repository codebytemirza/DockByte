# DOCK_BYTE

The DOCK_BYTE module provides tools for extracting text from PDF and TXT documents and enables interactive chat-based exploration of the extracted content using a language model. It leverages various libraries for document processing and integrates with Streamlit for a GUI-based interface.

## Features
- Extract text from PDF documents using PyMuPDF.
- Perform OCR on PDF documents using Tesseract.
- Extract text from TXT files.
- Use a language model to chat with the content of the documents.
- GUI support with Streamlit for interactive usage.

## Installation

```sh
pip install DOCK_BYTE
```

## Usage

```python
from dock_byte import chat_with_doc

chat_with_doc("gemma:2b", "data.txt", use_gui=True)
```
## Runing
```bash
streamlit CODE_FILE.py 
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Repository

For more information and to contribute, please visit the [GitHub repository](https://github.com/CodeByte-hash/DOCK_BYTE).

## Demo
[![Watch the video](https://img.youtube.com/vi/UDi3Nt91Tl4/maxresdefault.jpg)](https://youtu.be/UDi3Nt91Tl4)
