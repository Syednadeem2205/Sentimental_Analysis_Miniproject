# Valentine Compatibility Analyzer

## Project Description

The **Valentine Compatibility Analyzer** is a fun and interactive NLP-powered tool that analyzes conversations between couples to determine their romantic compatibility. Using **sentiment analysis, emotion classification, and keyword detection**, this tool assesses whether a couple can be potential Valentines based on their text messages. The system utilizes **Hugging Face Transformers** for NLP processing and **SQLite** for conversation storage.

## Features

- Stores and retrieves couple conversations from a SQLite database.
- Uses **sentiment analysis** to gauge the tone of messages.
- Employs **emotion classification** to identify the dominant feelings expressed.
- Performs **keyword analysis** to count romantic and negative words.
- Generates insights into relationship positivity and emotional balance.
- Predicts if a couple has strong Valentine potential based on conversation patterns.

## Technologies Used

- **Python**
- **SQLite3** (Database Management)
- **Hugging Face Transformers** (Sentiment & Emotion Analysis)
- **Pandas** (Data Handling)
- **Collections.Counter** (Emotion Aggregation)

## Installation & Setup

1. **Clone the Repository**

   ```sh
   git clone https://github.com/your-username/valentine-analyzer.git
   cd valentine-analyzer
   ```

2. **Install Dependencies**

   ```sh
   pip install sqlite3 pandas transformers torch
   ```

3. **Run the Program**

   ```sh
   python valentine_analyzer.py
   ```

## Usage

1. The program initializes an SQLite database with sample conversations.
2. It retrieves and displays a list of available couples.
3. Users can select a couple to analyze their conversation.
4. The system processes messages and provides insights into positivity, emotions, and keyword trends.
5. Finally, it predicts if the couple can be Valentine-compatible!

## Example Output

```
Available Couples:
1. couple_1
2. couple_2

Select a couple by entering the number: 1

Selected Couple: couple_1

Conversation:
Alice: I love you so much, darling!
Bob: I love you too, sweetheart!
Alice: You are my everything, my dear!
Bob: I miss you so much, my love.

Analysis Results:
Positive Messages: 4
Negative Messages: 0
Average Sentiment Score: 0.94
Romantic Words Count: 5
Negative Words Count: 0
Prediction: Yes! They can be your Valentine! ❤ (Top Emotion: Love)
```

## License

This project is open-source and available for modification and use.

