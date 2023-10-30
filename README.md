# Telegram C2
  Command and control a server via telegram bots.

### Installation 
- Create a telegram bot
- Edit main.cpp. Set ```bot_api_key``` to the bot's api key and ```user_id``` to your telegram id
- Install the following dependencies
  ```console
  ```
- Compile using the command below
  ```bash

  ```
- Deploy to target
- Start telegram bot

### Usage
  ```console
    /start               - Start telegram bot
    /viewFile <path>     - Display the contents of a file
    /listDir <path>      - List the files in a directory
    /downloadFile <path> - Download file from server to telegram
    /services            - List running services
    /screenshot          - Take screenshot of desktop
    /webcam              - Take image if webcam is supported
  ```