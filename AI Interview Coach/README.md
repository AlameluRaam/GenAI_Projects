# AI Interview Coach

This app helps you practice interviews by using Cohere's AI to simulate a job candidate.

The tool gives you detailed, well-structured answers to interview questions based entirely on the resume and job description you provide. It’s like having an AI coach who knows your background and the role requirements.

## Features

Provide Context: Easily upload your resume and the job description.

Ask Questions: Ask any interview question you want.

Get Smart Answers: Receive detailed answers that the AI generates using your context.

Review History: View all your practice questions and answers in one scrollable list.

Start Over: Clear the session anytime to practice for a new job.

## How to Run the App (Setup Guide)
To get this app running on your computer, follow these simple steps:

Get the Code: Open your command line and download the project code.
1. Clone the repository:
   ```bash
   git clone https://github.com/rrrreddy/interview-assistant.git
   cd interview-assistant
    ```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Create a .env file in the root directory with your Cohere API key:
```
COHERE_API_KEY=your-cohere-api-key
```
4. Run the application:

```
streamlit run app.py
```






