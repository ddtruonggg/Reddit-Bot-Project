# Reddit Information Helper Bot

## Project Overview
This is a Python-based Reddit bot that utilizes the **PRAW** (Python Reddit API Wrapper) to interact with the Reddit API. The bot's primary goal is to enhance user experience by providing instant information based on specific triggers or keywords.

## Key Features
- **Keyword Triggering:** Responds to specific commands (e.g., `!info <topic>`).
- **Data Integration:** Fetches data from external APIs to provide accurate, real-time information.
- **Smart Formatting:** Delivers responses in clean, easy-to-read Markdown tables.

## Technical Stack
- **Language:** Python 3.x
- **Libraries:** PRAW, Requests, Dotenv
- **Deployment:** Hosted on a private VPS

## Ethical Standards
- **Rate Limiting:** The bot respects Reddit's API rate limits to prevent spam.
- **Opt-out:** Users and Subreddits can easily opt-out of the bot's services.
- **Transparency:** All bot actions are logged and identifiable by its unique signature.

## Installation & Setup
*(This section is for development purposes)*
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Configure `.env` with Reddit API credentials (client_id, client_secret, user_agent).
4. Run `python bot.py`.
