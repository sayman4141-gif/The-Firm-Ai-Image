# The Firm AI - Image Generation Bot

A Telegram bot that converts text to images using advanced AI technology. Simply send a description of the image you want, and the bot will generate a unique image for you.

## Features
- High-quality text-to-image generation
- Simple and intuitive interface
- Supports various art styles and detailed prompts
- Error handling and user-friendly messages

## Requirements
- Python 3.7 or later
- Telegram Bot Token
- The Firm AI API Key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/the-firm-ai-bot.git
   cd the-firm-ai-bot
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Linux/Mac
   .\venv\Scripts\activate  # On Windows
   ```

3. Install the requirements:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file and add your API keys:
   ```
   TELEGRAM_TOKEN=your_telegram_bot_token
   DEEPAI_API_KEY=your_deepai_api_key
   ```

## Running the Bot

To run the bot locally:
```bash
python bot.py
```

## Bot Commands
- `/start` - Show welcome message and instructions
- `/help` - Show help and usage tips
- Send any text description to generate an image

## Deployment

### Heroku
1. Create a new Heroku app
2. Add a `Procfile` with:
   ```
   worker: python bot.py
   ```
3. Deploy your code and set the environment variables in Heroku settings

### VPS (Recommended for Production)
1. Install Python and required dependencies
2. Set up a process manager like PM2 or Supervisor
3. Run the bot as a service

## License
This project is licensed under the MIT License.
