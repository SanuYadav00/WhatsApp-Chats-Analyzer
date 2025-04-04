# WhatsApp Chats Analyzer

Analyze and gain insights from your WhatsApp chat data using this Python-based tool. Whether you're interested in message frequency, participant activity, or content trends, this analyzer provides a detailed examination of your conversations.

## Features

- **Message Statistics**: Calculate the total number of messages, words, media files, and links shared.
- **Participant Analysis**: Identify the most active participants based on message count and average message length.
- **Timeline Insights**: Visualize messaging activity over time, including daily, monthly, and hourly trends.
- **Emoji Usage**: Discover the most frequently used emojis and their distribution among participants.
- **Word Cloud**: Generate a word cloud to highlight the most commonly used words in the chat.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SanuYadav00/WhatsApp-Chats-Analyzer.git

2.  **Navigate to the Project Directory**:
    cd WhatsApp-Chats-Analyzer

3.  **Install Required Dependencies**: Ensure you have Python installed on your system. Install the necessary packages using pip:
   pip install -r requirements.txt


## Usage
 1. **Export Your WhatsApp Chat**
**Follow these steps in WhatsApp**:
# 1. Open the desired chat.
# 2. Tap on the three-dot menu (⋮) in the top-right corner.
# 3. Select "More" > "Export chat".
# 4. Choose "Without media" when prompted.
# 5. Save the exported `.txt` file to your computer.

2. **Run the Analyzer**
Place the exported chat file in the project directory and rename it to chat.txt (or update the filename in the script accordingly). Then, execute the following command:
python app.py


## Example Output
**Below is an example of what the output might look like after running the analyzer**:
Total Messages       : 10,000
Total Words          : 50,000
Most Active Participant : User A (3,000 messages)
Peak Activity Hour   : 8 PM - 9 PM
Most Used Emoji      : 😂

[Visualizations generated: timelines, heatmaps, word clouds]


