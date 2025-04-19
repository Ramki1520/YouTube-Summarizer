# YouTube Summarizer

![Youtube Summary App](https://github.com/ballasaimounika/YouTube-Summarizer/blob/main/play.gif)


## Why YouTube Summarizer

For many YouTube videos, only 50–60% of the total content is relevant and informative, while the rest may be filler or unimportant.</ul>

The **YouTube Summarizer** extracts and condenses the important points of the video, providing a concise and easily understandable summary.</ul>

By summarizing the transcripts of such videos, you can quickly identify the important insights, saving time and effort by not needing to go through the entire video.</ul>

This automatic summarization allows you to focus on what matters most without wading through hours of content.</ul>


## How it Works

![Youtube Summarizer](https://github.com/ballasaimounika/YouTube-Summarizer/blob/main/structure.JPG)


## App Features

1. **Video Transcript Extraction**: Automatically extracts transcripts from YouTube videos using the video URL.

2. **Multiple Summarization Techniques**:Supports various summarization algorithms, including Gensim, NLTK, SpaCy, and TF-IDF for extractive summarization, as well as T5-based abstractive summarization.

3. **Language Translation**: Translates summaries into multiple languages using the deep_translator library.

4. **Text-to-Speech**: Converts summaries into audio format, making the content more accessible.
 
5. **Customizable Summary Length**: Allows users to choose their preferred summary length.

6. **Interactive UI**: Built with Streamlit, the application provides an easy-to-use interface for all functionalities.


## Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **NLP Libraries**: NLTK, spaCy, Gensim, TF-IDF, T5
- **Translation**: deep_translator  
- **Text-to-Speech**: gTTS  
- **Other**: YouTube Transcript API


## Installation

System Requirement: Python 3.7

1. Clone the repository:
    ```git clone https://github.com/ballasaimounika/YouTube-Summarizer.git```
2. Navigate into the project directory:
   ```cd YouTube-Summarizer```
3. Install the required dependencies:
   ```pip install -r requirements.txt```
4. Run the application:
   ```streamlit run app.py```


## App Usage

1. **Enter YouTube Video URL**: Paste the URL of the YouTube video you want to summarize into the input field.

2. **Select Summarization Type**: Choose between extractive and abstractive summarization methods.

3. **Choose Summarization Algorithm**: If you select extractive summarization, pick one of the available algorithms (Gensim, NLTK, SpaCy, or TF-IDF).

4. **Set Summary Length**: Adjust the slider to select the desired length of the summary relative to the original transcript.
   
5. **Select Language for Translation**: Choose the language in which you want the summary to be translated.

6. **Generate Summary**: Click the 'Summarize' button to process the video transcript and generate the summary.

7. **Listen to Summary**: You can play the audio version of the summary if you prefer to listen instead of reading.
