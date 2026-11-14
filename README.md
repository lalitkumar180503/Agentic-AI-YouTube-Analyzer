# 🎥 Agentic AI YouTube Analyzer

An AI-powered YouTube Video Analyzer built using **Python, Agno, OpenAI GPT-5.2, and Streamlit**. This application analyzes YouTube videos and generates structured reports with video overviews, timestamps, topic segmentation, and key learning points.

## 🚀 Project Overview

The Agentic AI YouTube Analyzer is designed to help users understand YouTube video content more efficiently.

Users can enter a YouTube video URL through a Streamlit web interface, and the AI agent analyzes the video content and generates an organized analysis report.

## ✨ Features

- **Video Overview:** Provides basic video information and identifies the video type.
- **Timestamp Creation:** Generates meaningful video segments with start and end times.
- **Content Organization:** Groups related topics and identifies major themes.
- **Key Learning Points:** Highlights important concepts and practical demonstrations.
- **Structured Analysis:** Presents the analysis in a clear, organized Markdown format.
- **Interactive Interface:** Simple web interface built with Streamlit.

## 🛠️ Technologies Used

- Python
- Agno Framework
- OpenAI GPT-5.2
- YouTubeTools
- Streamlit
- Python-dotenv

## 📂 Project Structure

```text
Agentic-AI-YouTube-Analyzer/
│
├── youtube_analyzer.py    # AI agent configuration
├── app.py                 # Streamlit application
├── .env                   # API key configuration
├── .gitignore             # Git ignored files
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Agentic-AI-YouTube-Analyzer.git
```

### 2. Navigate to the Project Directory

```bash
cd Agentic-AI-YouTube-Analyzer
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create a `.env` file in the project directory:

```env
OPENAI_API_KEY=your_openai_api_key
```

Replace `your_openai_api_key` with your actual OpenAI API key.

### 5. Run the Application

```bash
streamlit run app.py
```

The Streamlit application will open in your browser.

## 🖥️ How to Use

1. Open the application.
2. Enter a valid YouTube video URL.
3. Click the **Analyze Video** button.
4. Wait for the AI agent to process the video.
5. View the generated analysis report.

## 🎯 Analysis Output

The application is instructed to generate:

- Video overview and metadata
- Video content structure
- Meaningful timestamps
- Main topics and themes
- Topic progression
- Key learning points
- Practical demonstrations and references

## 🔐 Environment Variables

Keep your API key private. Never upload your `.env` file or expose your API key on GitHub.

## 👨‍💻 Author

**Lalit Kumar Saraswat**

- GitHub: https://github.com/lalitkumar180503
- LinkedIn: https://www.linkedin.com/in/lalit-kumar-saraswat-954873252

---

⭐ If you find this project useful, consider giving it a star!
