# Whatsapp Chat Analyzer

## Overview

The **Whatsapp Chat Analyzer** is a tool for analyzing WhatsApp chat data to gain insights into messaging patterns, user activity, and more. It provides various statistics and visualizations including message counts, word clouds, activity maps, and emoji analysis. This tool is designed to work with exported WhatsApp chat files.

## Features

- **Top Statistics**: Displays total messages, total words, media shared, and links shared.
- **Monthly Timeline**: Shows a plot of message counts over months.
- **Daily Timeline**: Shows a plot of message counts over days.
- **Activity Map**: Provides insights into the most active days and months.
- **Weekly Activity Map**: Visualizes user activity by day and time.
- **Word Cloud**: Generates a word cloud from chat messages.
- **Most Common Words**: Lists the most frequently used words in the chat.
- **Emoji Analysis**: Shows a table and pie chart of emojis used.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
    cd whatsapp-chat-analyzer
    ```

2. **Set Up the Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**

    ```bash
    streamlit run app.py
    ```

2. **Upload a WhatsApp Chat File**

   - Click on the sidebar option to upload your chat file (must be in `.txt` format).
   - Select the user for whom you want to analyze the chat data or choose "Overall" to view group-level statistics.

3. **Explore the Analysis**

   - Use the sidebar to select the user and view various statistics, timelines, activity maps, word clouds, and emoji analysis.

## Project Structure

- **`app.py`**: Main script for running the Streamlit application.
- **`preprocessor.py`**: Handles preprocessing of WhatsApp chat data.
- **`helper.py`**: Contains functions for generating various analyses and visualizations.
- **`stop_hinglish.txt`**: File containing stop words for text analysis.
- **`requirements.txt`**: Lists the Python packages required for the project.

## Requirements

- Python 3.x
- Streamlit
- Matplotlib
- Seaborn
- Urlextract
- Wordcloud
- Pandas
- Emoji

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source libraries used in this project, including Streamlit, Matplotlib, and Wordcloud.
- Special thanks to the contributors and maintainers of these libraries.

---

For more details or if you encounter any issues, feel free to open an issue or contact the project maintainer.

