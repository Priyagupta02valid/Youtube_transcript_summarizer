# Youtube_transcript_summarizer
Developed an AI-powered application that extracts transcripts from YouTube videos, summarizes them into concise insights, and performs sentiment analysis to evaluate the overall tone of the video.


Key Features:

Transcript Extraction: Automatically retrieves subtitles/transcripts from YouTube videos using the youtube-transcript-api.

Summarization: Uses Google’s Gemini API (via google-generativeai) to generate human-like summaries of video content.

Sentiment Analysis: Applies Hugging Face’s Transformer models to classify the transcript as Positive, Negative, or Neutral.

Environment Setup: Managed sensitive keys using .env files and dotenv for secure API key handling.

Deployment Ready: Code written in Google Colab with modular functions for easy scaling or integration into web apps.

Tech Stack:

Python

Google Gemini API (google-generativeai)

Hugging Face Transformers

FAISS (for text/vector search, optional)

YouTube Transcript API

Google Colab

Impact / Learning Outcomes:

Automated video content understanding without manual watching.

Gained hands-on experience with LLMs (Gemini), NLP pipelines, and API integration.

Combined summarization + sentiment analysis for a more insightful video analysis tool.
