# PterodactylDiscord v1.0.0
* **Note**: if you can't connect your server using this bot please check [FAQ](FAQ.md), or ask for help on the [support server](https://discord.gg/delopfelo-development).

[Official Discord Server](https://discord.gg/delopfelo-development)
Here you can get help and download the latest version of the pack, find a full installation tutorial, try the pack without installing it on our test-server. 
You can also contact us by [email](mailto:delopfelo.development@gmail.com).

*Is it up to date?* So far supported versions are: **1.21.111** (bedrock latest), We plan to add support for later versions.


And if you want to donate you can do it [here](https://donationsalerts.com/delopfelo)!
## Installation
Short version (for expert users only) is this: 
* [invite](https://discord.com/invite_bot) bot, run to [app](https://github.com/delopfelo/BinariosBridge/src/botConsoleApp), install `BinariosBridge v1.0.0 [RP-BP].mcaddon` on your world/server.
* ??
* ??

Don't forget to check our [YouTube](https://www.youtube.com/@Esploratori-Development/featured) tutorials: installation on [hosted servers](https://youtu.be/1NTrhmW43eE), and on [Aternos](https://youtu.be/fcM9pY2JhMw)!
### Discord setup
1. Invite BedrockBridge discord bot to your discord-server using this [link](https://discord.com/api/oauth2/authorize?client_id=1041838898843762769&permissions=2684357632&scope=bot%20applications.commands).
2. Choose the channel you want to have bedrock-chat streamed to and run `/setup` in it.
3. Request a new token by running `/new-token`. Keep it safe.

**If the messages are not streamed and your server is connected, give the bot admin permissions, then run `/setup`.** Successful setup is needed in order to stream chat. If you need help don't hesitate to contact staff on the official discord server.
### Bedrock setup
4. [Download](https://raw.githubusercontent.com/InnateAlpaca/BedrockBridge/main/Bedrock-Bridge.mcaddon) BedrockBridge addon.
5. Install BedrockBridge addon on your world, making sure to enable experiments (**beta API**) and ignore console error logs[^1].
6. Upload the world back to your server.
7. Navigate to `<main folder>/config/default` and open `permissions.json`. Add the following line to the file `"@minecraft/server-net"` making sure that it respects JSON format[^2]. *Note: if errors persist just replace your `permissions.json` file with [this file](https://github.com/InnateAlpaca/BedrockBridge/blob/main/BedrockBridg_Serverpack/config/default/permissions.json).*
8. Start your server, join the game, and run `!setup`. Now fill the form. 

*Note: If you are not op or if cheats are disabled, in order to open the setup form please run the following command in server-console while you are connected to the server: `execute as <your username> run scriptevent esploratori:setup` (e.g. `execute as InnateAlpaca run scriptevent esploratori:setup`). Now close the chat and fill the form.*
[^1]: The error is caused by usage of modules that are server-only and can't be used in single world. The world will have no issue when running on a server.
[^2]: You can use [this tool](https://jsonchecker.com/) to verify if the modified file is valid, if it's invalid you are most surely missing some comma or quote.

*Check the [documents](DOCS.MD) in order to see what commands you can run from discord, and enjoy!!*

### Aternos
**New Installation for Aternos users** (since bridge 1.4.2)
* download the pack using the `/download` discord command.
* drop the .mcaddon pack into `Menu>Files>packs`
* enable `Worlds>Options>Beta API`
* start the server and enjoy!

If you have problems you can refer to the new [youtube tutorial](https://www.youtube.com/watch?v=fcM9pY2JhMw).
