# Build-and-Deploy-an-End-to-End-AI-Agent-Chatbot-with-Docker

## Description
In this project, I developed and deployed an end-to-end AI Agent Chatbot utilizing a combination of Docker, LangGraph, FastAPI, and Streamlit for the user interface. The project serves as a comprehensive guide, covering everything from the fundamentals of Docker to advanced concepts such as images, containers, and port binding.

### Key Features:
- **AI Agent Chatbot**: Leverage the power of language models to create an interactive chatbot capable of understanding and responding to user queries.
- **Docker Integration**: Learn the basics of Docker, including how to create and manage images and containers, ensuring a smooth deployment process.
- **FastAPI Backend**: Utilize FastAPI to build a robust and efficient backend for handling API requests and serving the chatbot's functionality.
- **Streamlit UI**: Implement a user-friendly interface using Streamlit, allowing users to interact with the chatbot seamlessly.

This project not only demonstrates the integration of various technologies but also provides a step-by-step walkthrough of the entire development and deployment process, making it an excellent resource for anyone looking to build and deploy AI applications.

## Features
- RESTful API for interacting with the language model
- Asynchronous support for improved performance
- Easy to extend and customize
- Built-in error handling

## Requirements
- Python 3.7 or higher
- FastAPI
- Uvicorn
- Docker
- Streamlit
- Any other dependencies specified in `requirements.txt`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shivam2203/AI-Agent-Chatbot-with-Docker.git
   cd AI-Agent-Chatbot-with-Docker
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the FastAPI server:
   ```bash
   uvicorn app:app --reload
   ```

2. Open your browser and navigate to `http://127.0.0.1:8000/docs` to access the interactive API documentation.

3. Use the API endpoints to interact with the language model.

## API Endpoints
- `POST /generate`: Generate text based on the provided input.
- `GET /health`: Check the health status of the API.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## Acknowledgments
- [FastAPI](https://fastapi.tiangolo.com/) - The web framework used for this project.
- [Uvicorn](https://www.uvicorn.org/) - The ASGI server used to run the FastAPI application.
- [Streamlit](https://streamlit.io/) - The framework used for building the user interface.
- [Docker](https://www.docker.com/) - The platform used for containerization.
