# WhatsApp Chat Analyzer

WhatsApp Chat Analyzer is a Python-based tool for analyzing and visualizing statistics from your WhatsApp group chat. The tool provides insights such as total messages, word count, media shared, links shared, monthly and daily timelines, activity maps, and more.

## Features

- **Total Messages:** View the total number of messages in the chat.
- **Word Count:** Analyze the total number of words used in the chat.
- **Media and Links:** Check the number of media messages and shared links.
- **Monthly and Daily Timelines:** Visualize the chat activity over months and days.
- **Activity Maps:** Identify the most active days and hours.
- **Most Busy Users:** Identify the most active users in the group.
- **Most Common Words:** Find the most frequently used words (excluding common stop words).
- **Emoji Analysis:** Explore emoji usage patterns in the chat.

## Getting Started

### Prerequisites

- Python 3.x
- Install required packages: `pip install -r requirements.txt`

### Usage

1. Clone the repository: `git clone https://github.com/your-username/whatsapp-chat-analyzer.git`
2. Navigate to the project directory: `cd whatsapp-chat-analyzer`
3. Run the app: `streamlit run app.py`

### How to Analyze a WhatsApp Chat

1. Export the WhatsApp chat from the group.
2. Open the WhatsApp Chat Analyzer.
3. Upload the exported chat file using the file uploader.
4. Select the user or choose "Overall" for group-level analysis.
5. Click the "Show Analysis" button to generate insights and visualizations.

## File Structure

- `app.py`: Main Streamlit application file.
- `preprocessor.py`: Module for preprocessing the raw chat data.
- `helper.py`: Module containing helper functions for data analysis.
- `stop_hinglish.txt`: Stop words specific to the Hinglish language.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [Streamlit](https://streamlit.io/) for the interactive app framework.
- Emoji analysis inspired by [emoji](https://pypi.org/project/emoji/) library.

