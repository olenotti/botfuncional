# Discord Bot Application

This project is a simple Discord bot built using Node.js and the discord.js library. It serves as a template for creating your own Discord bots with basic command and event handling.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Events](#events)
- [Environment Variables](#environment-variables)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/discord-bot-app.git
   ```

2. Navigate to the project directory:
   ```
   cd discord-bot-app
   ```

3. Install the required dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your Discord bot token:
   ```
   DISCORD_TOKEN=your_bot_token_here
   ```

## Usage

To start the bot, run the following command:
```
node src/index.js
```

Make sure your bot is invited to a server and has the necessary permissions to read messages and send messages.

## Commands

The bot currently supports the following command:
- `!example`: This command is defined in `src/commands/exampleCommand.js`. You can customize it to add more functionality.

## Events

The bot listens for various events, including:
- `ready`: This event is handled in `src/events/ready.js`. It triggers when the bot successfully connects to Discord.

## Environment Variables

The project requires the following environment variable:
- `DISCORD_TOKEN`: Your Discord bot token, which can be obtained from the Discord Developer Portal.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.