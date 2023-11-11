# Telegram C2
  Command and control a server via telegram bots.

### Installation 
- Create a telegram bot
- Edit main.py, set ```BOT_API_KEY``` to the bot's api key and ```telegram_user_id``` to your telegram id
- Install the following dependencies
  
  ```console
  pip install -r requirements.txt
  ```
- Compile to standalone binary for easier deployment

  ```bash
  pip install -U pyinstaller
  pyinstaller main.py
  ```
- Deploy to target
- Start telegram bot

### Usage
  ```console
    /start                 - Start telegram bot
    /viewFile <path>       - Display the contents of a file
    /listDir <path>        - List the files in a directory
    /downloadFile <path>   - Download file from server to telegram
    /services              - List running services
    /screenshot            - Take screenshot of desktop
    /webcam                - Take image if webcam is supported
    /video <duration(sec)> - Record video from webcam
  ```

### Screenshots

<div align="center">
  <img src="https://github.com/Tomiwa-Ot/telegram-c2/assets/37912743/888bdc50-56f9-4fef-a0f0-8567184a9230" width="50%" /><br />
  <img src="https://github.com/Tomiwa-Ot/telegram-c2/assets/37912743/7413d748-29d9-42a2-85de-1f82683a4a7d" width="50%" /><br />
  <img src="https://github.com/Tomiwa-Ot/telegram-c2/assets/37912743/2e1657db-0594-473a-bbe9-12111b4a9717" width="50%" /><br />
  <img src="https://github.com/Tomiwa-Ot/telegram-c2/assets/37912743/87378bbf-a403-497a-80be-d813c9d3e711" width="50%" /><br />
  <img src="https://github.com/Tomiwa-Ot/telegram-c2/assets/37912743/a741afbf-0441-4522-b311-346de9048527" width="50%" /><br />
</div>
