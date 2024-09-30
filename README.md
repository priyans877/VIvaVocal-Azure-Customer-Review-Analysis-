# ViveVocal: Azure Customer Review Analysis

## Overview
**ViveVocal** is a powerful AI-driven solution that transforms customer feedback into actionable insights by leveraging **Azure Speech Services** for speech-to-text conversion and **Azure Language Services** for sentiment analysis, language detection, key phrase extraction, and entity recognition.

This project allows users to submit reviews through three different methods: speaking directly, uploading a file, or typing text. It then processes the input to extract important details such as sentiment, key phrases, and entities, helping businesses gain deeper insights into customer feedback and trends.

## Features
- **Multimodal Input**:
  - 🗣️ **Speech Input**: Convert spoken feedback into text using Azure Speech Services.
  - 📁 **File Upload**: Process uploaded audio or text files for analysis.
  - ⌨️ **Text Input**: Directly analyze typed text reviews.
  
- **Sentiment Analysis**: Understand the emotional tone behind the feedback.
  
- **Language Detection**: Automatically detect the language of the feedback.
  
- **Key Phrase Extraction**: Extract important topics and phrases that summarize the feedback.
  
- **Entity Recognition**: Identify key entities such as products, services, locations, or brands and link them to relevant sources for further insights.

## Why It's a Game Changer
By identifying key phrases and entities, businesses can:
- Address specific customer concerns.
- Spot emerging trends.
- Respond proactively to real-time feedback.

Additionally, seeing how entities such as products or competitors are discussed in customer reviews offers businesses a unique competitive advantage in understanding customer sentiment and making informed decisions.

## How It Works
1. **Speech-to-Text**: If the user provides an audio review, Azure Speech Services converts it to text.
2. **Text Processing**: The text (from speech, file, or typed) is analyzed using Azure Language Services.
3. **Sentiment Analysis**: Detects whether the feedback is positive, negative, or neutral.
4. **Language Detection**: Identifies the language of the feedback.
5. **Key Phrase Extraction**: Highlights the most important phrases or topics from the review.
6. **Entity Detection**: Recognizes specific entities (e.g., products, brands) and links them to additional sources or context.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/priyans877/VIvaVocal-Azure-Customer-Review-Analysis-.git
    cd VIvaVocal-Azure-Customer-Review-Analysis-
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up Azure resources:
    - Create an **Azure Speech Services** resource for speech-to-text conversion.
    - Set up **Azure Language Services** for sentiment analysis, key phrase extraction, and entity recognition.

4. Update your configuration settings in the project to include the **Azure API keys**.

## Usage

1. Start the application by running the following command:
    ```bash
    streamlit run app.py
    ```

2. Users can provide reviews in the following ways:
   - **Speak** directly into the microphone.
   - **Upload** a file (audio or text).
   - **Type** text manually.

3. The output will display:
   - Sentiment analysis (positive, neutral, negative).
   - Detected language.
   - Key phrases from the review.
   - Entities identified and links to those entities for more information.

## Technology Stack
- **Azure Speech Services**: For converting speech to text.
- **Azure Language Services**: For sentiment analysis, key phrase extraction, and entity detection.
- **Python**: Core programming language for the project.
- **Streamlit**: Front-end framework for creating the user interface.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any improvements or suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was developed as part of training provided by **ICT Academy** and **Infosys**.
