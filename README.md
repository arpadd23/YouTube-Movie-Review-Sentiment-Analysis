YouTube Movie Review Sentiment Analysis
## 📈 Overview
Welcome to the YouTube Movie Review Sentiment Analysis project! This repository features a detailed analysis of YouTube video transcripts to determine public sentiment towards the new Deadpool movie, helping you decide whether to catch it in theaters or wait for its home release.

## 🛠️ Features
## ◆ Transcript Downloading
-Downloads automatic captions for specified YouTube videos using the YouTube Transcript API.

## ◆ Sentiment Analysis
-Performs sentiment analysis using the lvwerra/distilbert-imdb model from Hugging Face Transformers.

-Aggregates sentiments to conclude the overall opinion from popular YouTubers.

## ◆ Results Interpretation
-Displays individual video sentiments and calculates the majority sentiment to guide viewing decisions.

## 📊 Dataset
-The project analyzes captions from eight YouTube videos, utilizing the automatic captions provided by YouTube to assess sentiment about the new Deadpool movie.

## 📚 Project Structure
-task_movie_review_sentiments.ipynb: The Jupyter Notebook containing the full analysis workflow.

-README.md: Documentation for the project setup and usage.

## 💾 Installation
Clone the Repository
```bash

git clone https://github.com/yourusername/YouTube-Movie-Review-Sentiment-Analysis.git
cd YouTube-Movie-Review-Sentiment-Analysis
```
Install Dependencies
```bash

pip install youtube-transcript-api transformers torch
```
## 🚀 Usage
Start the Notebook

-Launch JupyterLab or Jupyter Notebook.

-Navigate to the project directory.

-Open task_movie_review_sentiments.ipynb.

##  Execute the Analysis
-Run the cells sequentially to process the video transcripts and perform sentiment analysis.

## 🌟 Contributing
Interested in contributing? Great! Here's how you can help:

-Fork the repository.

-Create your feature branch (git checkout -b feature/AmazingFeature).

-Commit your changes (git commit -am 'Add some AmazingFeature').

-Push to the branch (git push origin feature/AmazingFeature).

-Open a pull request.

## 📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## 🙌 Acknowledgments
-YouTube Transcript API for easy access to video captions.

-Hugging Face Transformers for providing the powerful sentiment analysis model.

-lvwerra for the distilbert-imdb model used in this project.
