---

# OIBSIP-Task-3

This repository contains the code for **OIBSIP-Task-3**, which is part of the **Internship at Oasis Infobyte**. The task involves the creation of a solution related to various AI/ML applications and chatbot development.

## Project Description

This project includes the implementation of several features:
- **Chatbot Development**: A chatbot designed to answer questions using Llama.
- **Fine-Tuning**: The chatbot model is fine-tuned on educational data.
- **Data Scraping**: The scraping and processing of educational website data to generate a dataset for chatbot training.
- **Question-Answer Pair Generation**: Dynamic creation of question-answer pairs using Zephyr AI model.
- **Self-learning Feature**: Caching mechanism to store and reuse new question-answer pairs.

## Features

- **Fine-Tuning Llama**: The model is fine-tuned on educational website data for better accuracy in answering questions related to the curriculum, subjects, and contact information.
- **Web Scraping**: A script to extract content from educational websites and generate structured data for the chatbot.
- **Dynamic Question-Answer Generation**: The system generates question-answer pairs dynamically using AI models.
- **Real-time Processing**: Content is scraped and processed in real-time, with the chatbot providing answers instantly.
- **Caching**: The chatbot uses a caching system to store new question-answer pairs for future use, enabling self-learning.

## Prerequisites

Make sure you have the following installed:
- Python 3.x
- Flask
- Llama
- Zephyr AI Model
- Dependencies listed in `requirements.txt`

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/sneha280904/OIBSIP-Task-3.git
   ```

2. Navigate into the project directory:
   ```
   cd OIBSIP-Task-3
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Start the Flask server:
   ```
   python app.py
   ```

2. Access the chatbot via the local server:
   ```
   http://localhost:5000
   ```

3. Interact with the chatbot, ask questions, and it will generate answers based on the fine-tuned model and dynamically generated data.

## File Structure

```
OIBSIP-Task-3/
│
├── app.py                # Main Flask application
├── model.py              # Model and chatbot logic
├── data/                 # Folder containing scraped and processed data
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## Contributing

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request to merge changes.

## License

This project is licensed under the MIT License.

---
