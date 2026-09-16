# Alzheimer's Early Detection 

## Project Overview

This project focuses on developing an AI-based system for the early detection of Alzheimer's disease using **Natural Language Processing (NLP)** and speech recognition techniques.

The system analyzes speech recordings, converts spoken language into text, and examines linguistic patterns that may be associated with cognitive decline. Machine learning and deep learning models are then used to estimate the likelihood of Alzheimer's disease based on the analyzed speech data.

The project combines **speech recognition, NLP, machine learning, deep learning, and a React-based web interface** to provide an interactive platform for speech-based analysis.



## Installation

Follow the steps below to set up the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/42bismuth/Alzheimer-Detection.git
cd Alzheimers-Detection
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 3. Install Python Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### 4. Install Frontend Dependencies

Navigate to the frontend directory and install the required packages:

```bash
cd client
npm install
```

## Usage

The application consists of a Python backend and a React frontend.

### Run the Backend

Run the backend application using:

```bash
python app.py
```

### Run the Frontend

Open another terminal, navigate to the client directory, and start the React application:

```bash
cd client
npm start
```

Once both services are running, the web interface can be used to upload and analyze speech input.

## Features

### Speech Recognition

The application uses the **AssemblyAI speech-to-text API** to convert audio recordings into text for further analysis.

### NLP Analysis

The transcribed speech is processed using Natural Language Processing techniques to examine linguistic characteristics and patterns associated with Alzheimer's disease.

The project applies multiple NLP approaches to improve the analysis of speech transcriptions.

### Machine Learning Analysis

Different machine learning and deep learning approaches are used to analyze speech-derived text and classify the data.

### React-Based Interface

A modern web interface has been developed using **React**, allowing users to interact with the system and view speech analysis results in an accessible format.

The interface is designed to provide a straightforward workflow for submitting speech input and reviewing the resulting analysis.

## Dataset

The project uses the **DementiaBank** dataset.

### Source

**DementiaBank:**
https://www.tensorflow.org/datasets/catalog/dementiabank




