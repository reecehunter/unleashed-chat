# Unleashed.chat CLI Chat Wrapper

A CLI wrapper for [Unleashed.chat](https://unleashed.chat)'s chatbot service.

> This package has no official affiliation with [Unleashed.chat](https://unleashed.chat).

## Usage

1. Install the package.
   `pip install unleashed-chat`

2. Start it up.
   `unleashed-chat`
   On the first startup, it will prompt you for your [Unleashed.chat](https://unleashed.chat) API key. Enter it to continue to the chat bot.

3. Ask the chatbot whatever you want!

## Commands

Once in the app, you can use the following commands instead of asking the chatbot something.

- `/help`
  - Display a list of the possible commands.
- `/reset`
  - Clear the conversation memory to start a new session.
- `/modules`
  - Display a list of the available modules.
- `/setmodule`
  - Prompts you to input the model to use.
- `/exit`
  - Exit out of the application cleanly.

## Startup Flags

- `--help, -h`
  - Display information about Unleashed Chat CLI including a description and flags.
- `--set-api-key`
  - Prompts you to enter your [Unleashed.chat](https://unleashed.chat) API key to be saved within the application.

## Contributing

Feel free to make a pull request on [GitHub](https://github.com/reecehunter/unleashed-chat) to add or improve on features.