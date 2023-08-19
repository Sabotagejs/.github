![Sabotage.Js](https://raw.githubusercontent.com/Sabotagejs/.github/main/20230819_204644.png)


*Powerful Package that helps developing discord bot more easy*

# Features
@ Already included **interaction Event handler** ( you can use discord.js also to make custom Events, ready is Alr there) 

@ Easy Command handler setting 
```js
commandhandler(`${__dirname}/commands`, client) 
```

@ Register Global and Server slash commands easily
   
Registering global slash commands:
```js
registerGlobalCmd( `${__dirname}/commands`, clientId , token)
```
Registering server slash commands:
```js
registerServerCmd(`${__dirname} /commands`, clientId, guildId, token) 
```
# Example:

```js
const  { Daddyison, TheHeck, Clientuwu, HotEvents, MakeaSlash, loadammo, UwuGateIntentBit, commandhandler, registerGlobalCmd } = require('sabotagejs')
const token = process.env['token']
const client = new Clientuwu({ intents: [UwuGateIntentBit.Guilds] });

Daddyison(client)
console.log('hi')
loadammo(token, client)
commandhandler(`${__dirname}/commands`, client)
registerGlobalCmd( `${__dirname}/commands`, clientid, token)
```
daddyison(client) is a ready event and loadammo the login

# V1 
*Stay tuned for more updates*

