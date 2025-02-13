# Agentic RAG - AI Waiter Agent

## Overview
This project builds an AI Agent that acts as a virtual restaurant waiter. The agent interacts with customers, answers their menu-related queries, and provides friendly responses. The system is built using **LangChain** and **LangGraph**, integrating OpenAI's GPT-based language models to process user inputs effectively.

## Features
- **Conversational AI**: Uses OpenAI's GPT models to generate human-like responses.
- **Menu Assistance**: Provides detailed information about restaurant menu items.
- **Agentic Workflow**: Utilizes **LangGraph** to manage interactions efficiently.
- **RAG Integration**: Implements a Retrieval-Augmented Generation (RAG) system to fetch relevant menu details.

## Technologies Used
- **Python**
- **LangChain & LangGraph**
- **OpenAI API**
- **FAISS** (for vector similarity search)
- **Unstructured** (for document processing)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Agentic_RAG_Waiter.git
   cd Agentic_RAG_Waiter
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key in the environment variables.

## Usage
Run the Jupyter Notebook to initialize the agent:
```sh
jupyter notebook Agentic_RAG_Project.ipynb
```

## Future Enhancements
- Extend the agent to support multi-modal interactions (voice & text).
- Enhance menu understanding using structured databases.
- Deploy as a chatbot service.

## Contributing
Feel free to open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License.

