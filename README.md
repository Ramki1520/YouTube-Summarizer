# YouTube Summarizer 📹✍️

![YouTube Summarizer](https://img.shields.io/badge/YouTube%20Summarizer-v1.0-blue)

Welcome to the **YouTube Summarizer**! This tool helps you summarize YouTube videos, allowing you to save time and get the main points quickly. Whether you are a student, a professional, or just someone who loves learning, this tool is designed for you.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Quick Summaries**: Get concise summaries of YouTube videos.
- **User-Friendly Interface**: Easy to navigate with Streamlit.
- **Multi-Language Support**: Thanks to deep-translator, you can summarize videos in various languages.
- **Natural Language Processing**: Utilizes NLTK and spaCy for better text processing.
- **Text-to-Speech**: Listen to summaries using gTTS.

## Technologies Used

This project employs several powerful libraries and tools:

- **deep-translator**: For language translation.
- **gensim**: For topic modeling and summarization.
- **gtts**: Google Text-to-Speech for audio summaries.
- **nltk**: Natural Language Toolkit for text processing.
- **spaCy**: For advanced natural language processing.
- **streamlit**: For creating the web app interface.
- **t5**: Text-to-text transfer transformer for summarization.
- **tf-idf**: For term frequency-inverse document frequency analysis.
- **youtube-transcript-api**: To fetch video transcripts.

## Installation

To get started with the YouTube Summarizer, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ramki1520/YouTube-Summarizer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd YouTube-Summarizer
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

You can download the latest release from [here](https://github.com/Ramki1520/YouTube-Summarizer/releases). Make sure to execute the files as instructed.

## Usage

Using the YouTube Summarizer is simple:

1. Open the app in your web browser.
2. Paste the URL of the YouTube video you want to summarize.
3. Select your preferred language if needed.
4. Click on the "Summarize" button.
5. Read or listen to the summary provided.

## Contributing

We welcome contributions! If you have suggestions or improvements, feel free to fork the repository and submit a pull request. 

1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature/MyFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/MyFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For any issues or questions, please check the [Releases](https://github.com/Ramki1520/YouTube-Summarizer/releases) section or open an issue in the repository.

Thank you for using the YouTube Summarizer! We hope it helps you save time and learn efficiently.