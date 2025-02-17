# Automated Legal Document Analysis Platform

The **Automated Legal Document Analysis Platform** is a powerful web application designed to automate the analysis of legal documents. By extracting key information and identifying potential risks, the platform leverages **Natural Language Processing (NLP)** and **Machine Learning** models to help users understand complex legal clauses, detect hidden risks, and make informed decisions when handling legal documents like contracts.

This platform offers essential features such as document analysis, paraphrasing, sentiment analysis, and more, all built using modern technologies like **Next.js**, **Flask**, and **PyTorch**.

## Key Features

- **Automated Legal Document Analysis**: 
  - Automatically analyzes legal documents to extract critical clauses, terms, and identify potential risks.

- **Reading Comprehension Model**: 
  - Trained on the **SQuAD** dataset, this model allows users to extract information directly from legal documents, simplifying complex legal jargon.

- **CUAD Dataset**: 
  - A specialized dataset of 500 contracts designed to address common legal questions, providing users with better insights into essential clauses.

- **Paraphrasing Model**: 
  - Built using the **T5-base** model, this tool helps users understand complex contract clauses by generating paraphrases in simpler terms.

- **Sentiment Analysis**: 
  - Utilizes **TextBlob** to analyze the sentiment of legal clauses, offering valuable insights into the tone and potential risks embedded in the document.

- **User-Friendly Interface**: 
  - Developed with **Next.js**, the platform ensures a seamless and interactive experience for users, making it easy to navigate and use.

- **Flask Server Integration**: 
  - The front-end interface connects seamlessly with the machine learning models on the backend via a **Flask** server for efficient data processing.

- **Docker Containerization**: 
  - Simplifies deployment by packaging the entire application within **Docker**, enabling easy setup and scalability, regardless of the user's environment.

## Getting Started

### Prerequisites

1. **Node.js** (for running the frontend)
   - [Install Node.js](https://nodejs.org/)
2. **Python 3.8+** (for running the backend)
   - [Install Python](https://www.python.org/downloads/)
3. **Docker** (optional, for containerized setup)
   - [Install Docker](https://www.docker.com/get-started)

### Local Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Legal-AI-Project.git
   cd Legal-AI-Project
