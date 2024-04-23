# Medical Chatbot Project

## Overview

This project is a medical chatbot designed to assist users in finding information about medical conditions, treatments, and more. It leverages the power of Pinecone for vector search and Lama2.0 for natural language processing to provide accurate and relevant responses.

## Tech Stack

- **Pinecone**: A vector search engine used for finding similar items in high-dimensional spaces.
- **Lama2.0**: A natural language processing library used for understanding and generating human language.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8 or higher
- Pinecone account (sign up at [Pinecone](https://www.pinecone.io/))
- Lama2.0 library (install via pip: `pip install lama2`)

### Installation

1. Clone the repository:
git clone https://github.com/DakshBalyan-Coder/medical-chatbot.git

2. Navigate to the project directory:
cd medical-chatbot

3. Install the required Python packages:
pip install -r requirements.txt

4. Set up your Pinecone API key:
   - Create a `.env` file in the root of the project.
   - Add your Pinecone API key: `PINECONE_API_KEY=your_pinecone_api_key_here`

## Usage

To start the chatbot, run the following command:

python main.py


You can then interact with the chatbot by typing your queries into the console.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.


