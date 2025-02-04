# Youtube-Video-Summarize-to-predict-if-safe-for-children
This Python script downloads audio from a YouTube video, transcribes it using OpenAI Whisper, summarizes the transcript with BART, translates it using MarianMT, and analyzes its safety for children using a RoBERTa-based classifier.
## Tools used
1. **Programming Language**- Python
2. **YouTube Video Processing**- yt-dlp
3. **Speech-to-Text (Automatic Speech Recognition - ASR)**-OpenAI Whisper
4. **Text Summarization (NLP & LLMs)**- Hugging Face Transformers (BART - Abstractive Summarization)
5. **Text Classification (Content Safety Analysis)**- Hugging Face Transformers (RoBERTa - Hate Speech Detection)

## Applications
- **Child-Safe Content Filtering**: Parents can use the safety classification feature to check if a YouTube video is appropriate for kids.
- **Automated Lecture Summarization**: Students can upload long lecture videos and get a concise summary.
- **Helping Hearing-Impaired Users**: Deaf users can read transcriptions & summaries of YouTube videos they can't hear.
- **News Video Summarization**: News organizations can automatically summarize political debates, press conferences, or news reports.
