# OpenCord

This is a custom Discord client with GPT AI integration built using C# WinForms. It allows users to chat with an AI powered by OpenAI's GPT language model within a Discord server.

## Features

- Chat with an AI within a Discord server
- Use GPT-3.5 language model to generate responses
- **Customizable commands and responses**
- Easy to install and set up
- Built using C# WinForms

## Requirements

- .NET Framework 4.7.2 or later
- Discord account
- OpenAI API key (you can obtain this from the OpenAI website)

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/custom-discord-client.git`
2. Open the solution file `CustomDiscordClient.sln` in Visual Studio
3. Build the solution
4. Create a `.env` file and add your OpenAI API key: OPENAI_API_KEY=your_openai_api_key_here
5. Start the app from Visual Studio

## Usage

To use the app, log in to your Discord account and launch the app. Enter your OpenAI API key in the app settings. The app will connect to your Discord account and start listening for messages.

When a message is received, the app will send it to the OpenAI API to generate a response. The response will be displayed within the app, allowing for a seamless chat experience with the AI.

You can customize the commands and responses by editing the `Bot.cs` file. Refer to the [Discord API documentation](https://discord.com/developers/docs/intro) and the [OpenAI API documentation](https://beta.openai.com/docs/api-reference) for more information.

## Future Plans

While this app is currently built using C# WinForms, we plan to explore other cross-platform and mobile app options in the future.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
