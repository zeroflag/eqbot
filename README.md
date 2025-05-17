# eqbot
Simple AI chatbot written in Equinox 

```bash
# Install dependencies

$ luarocks install lua-dotenv 
$ luarocks install geminilua 
$ luarocks install equinox

# Create .env file

$ cat .env
api_key=<GEMINI_API_KEY>
mood=helpful
role=assistant

# Start the bot

$ equinox bot.eqx
```
