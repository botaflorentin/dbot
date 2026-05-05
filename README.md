# dbot

Discord bot starter. Build an LLM-powered chat bot with a custom persona.

Forked from [avathuy/dbot](https://github.com/avathuy/dbot) and lightly adapted for the workshop.

## .env

Create a `.env` file in the repo root:

```
TOKEN=your-discord-bot-token
OPENAI_KEY=your-openai-key
```

- Discord bot token: <https://discord.com/developers/applications>
- OpenAI key: <https://platform.openai.com/account/api-keys>

Make sure **Message Content Intent** is enabled for your bot in the Discord developer portal.

## hello bot

```
python discord_only.py
```

In your Discord server, type `$hello`.

## smart bot

```
pip install -r requirements.txt
python mybot.py
```

Type `$question <anything>` in your server. The bot answers with a custom persona defined in the prompt.

## Your turn

Add at least one new command of your own. Edit the prompt to fit your use case, save, restart the bot.
