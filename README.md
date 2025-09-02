# wings_Personal-Finance-Chatbot
 Personal Finance Chatbot is an AI-powered assistant that offers real-time, personalized guidance for managing savings, taxes, and investments through a conversational interface. It analyzes user inputs and financial data to provide actionable advice, making complex finance topics more accessible
 ClauseWise – Personal Finance Chatbot
ClauseWise – Personal Finance Chatbot

Overview
ClauseWise is an AI-powered chatbot designed to provide clear, concise, and actionable advice on savings, taxes, and investments. Built on the IBM Granite 3.2-2B Instruct model, ClauseWise leverages natural language understanding to guide users in making better financial decisions. The project integrates Gradio to deliver a simple, interactive web-based interface and uses 8-bit quantization for efficient deployment on limited hardware.

Key Features

* Personalized financial advice covering savings, taxes, and investments
* Memory-efficient model loading using bitsandbytes 8-bit quantization
* Easy-to-use Gradio-based chat interface for instant interaction
* Domain-specific system prompting to keep answers focused and relevant
* Lightweight deployment suitable for local or cloud environments

Architecture

1. Model: IBM Granite 3.2-2B Instruct, fine-tuned for instruction following
2. Backend: Hugging Face Transformers with PyTorch runtime
3. Optimization: bitsandbytes for 8-bit quantization
4. Frontend: Gradio ChatInterface for real-time chatbot experience

Installation

1. Clone the repository:
   git clone [https://github.com/your-username/clausewise-chatbot.git](https://github.com/venkatatharu/wings_Personal-Finance-Chatbot/tree/main)
   cd clausewise-chatbot

2. Install dependencies:
   pip install -r requirements.txt

   Or directly:
   pip install transformers torch gradio accelerate bitsandbytes

Usage

1. Run the application:
   python app.py

2. Access the chatbot via the browser:
   Local URL: [http://127.0.0.1:7860](http://127.0.0.1:7860)
   Public URL: Provided if share=True is enabled

Example Queries

* How much emergency fund do I need
* Best way to start investing 1000
* How to reduce tax burden
* Pay debt first or invest

Tech Stack

* Model: IBM Granite 3.2-2B Instruct
* Framework: Hugging Face Transformers
* Frontend: Gradio
* Runtime: PyTorch
* Optimization: bitsandbytes

Limitations

* This chatbot is for educational and informational purposes only. It does not replace professional financial advice.
* Responses may be generic or simplified depending on the query.

Future Enhancements

* Add conversation history for more context-aware responses
* Deploy as a FastAPI backend with a modern React or Next.js frontend
* Implement streaming responses for a real-time chat feel
* Expand financial coverage with budgeting and retirement planning modules
neric or simplified.
