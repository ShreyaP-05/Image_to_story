# 📖 Image to Story Generator (AI)

An AI-powered web application that converts an uploaded image into a creative short story using modern Generative AI models.

The system first analyzes the image, generates a textual description, and then transforms the description into a creative story using a large language model.

This project demonstrates practical implementation of Computer Vision + Generative AI + NLP pipelines.

## 🚀 Features

Upload any image (.jpg)

Automatically generate image caption

Convert caption into a creative story

Interactive web interface using Streamlit

AI-powered storytelling using LLMs

Real-time story generation

## 🧠 How the System Works

The pipeline follows these steps:

1️⃣ User uploads an image

2️⃣ Image captioning model generates description
Model used:
Salesforce BLIP Image Captioning

3️⃣ The generated caption becomes the story context

4️⃣ Large Language Model generates a creative story

5️⃣ The story is displayed in the web interface

## 🛠 Technologies Used

### Programming:

Python

### AI / ML:

Hugging Face Transformers

Image Captioning (BLIP)

Large Language Models

### Frameworks:

Streamlit

LangChain

### APIs:

Groq LLM API

### Libraries:

torch

transformers

langchain

streamlit

python-dotenv

## 📂 Project Structure

Image_to_story/

│

├── story.py              # Main Streamlit application

├── requirements.txt      # Python dependencies

├── README.md             # Project documentation

│

├── IMAGE                 # App logo or UI image

│

├── .env                  # API keys (not uploaded to GitHub)

│

└── assets/               # Optional folder for images

## ⚙️ Installation

### Clone the repository:

git clone https://github.com/ShreyaP-05/Image_to_story.git

cd Image_to_story

### Install dependencies:

pip install -r requirements.txt

## 🔑 Environment Variables

Create a .env file and add your API keys:

HF_TOKEN=your_huggingface_token

GROQ_API_KEY=your_groq_api_key

## ▶️ Running the Application

Run the Streamlit app:

streamlit run story.py

The app will open in your browser.

## 🖥 Application Interface

### User workflow:

1.Upload an image

2.AI analyzes the image

3.Caption is generated

4.A short story is created automatically

