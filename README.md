# TritiumBot v2

A simple, fast, and robust bot for the Signal messaging service.  

[!!! REQUIRES A VALID SIGNAL-CLI SETUP BEFOREHAND !!!](https://github.com/AsamK/signal-cli)  

To setup TritiumBot, start by running `cp ./config.jsonc.template ./config.jsonc`, then open `config.jsonc`, read the instructions and fill out all the necessary fields.  
Once you're done, run `npm install .` to install the node modules, then run `npm start` to start the bot.  
From there, you can configure the bot and add custom commands in the `commands.cjs` file (feel free to use one of the default commands as a base for your new commands).
