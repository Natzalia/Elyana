# Elyana
Elyana is an easy-to-use automod bot for Discord, created to secure servers and help you maintain a safe place for your members.

## Elyana's feature
Elyana is automated and fully customized automod, action taken when automodding are all customizable through the commands:

### Configuration commands:
- `Anti-spam`: Mutes/warns a user who sends x number of messages in less than 5s.
- `Ani-alts`: Quarantines/kicks an alt account who joins.
- `Anti-links`: Bans/kicks/mutes/warns anyone trying to send a phishing/scam links.
- `Anti-advertising`: Toggles on/off the anti-advertising system, you can whitelist/blacklist channels that can be advertised in.
- `Anti-profanity`: Deletes/hides a message that contains a blacklisted word.
- `Autoresponse`: Auto respond to a trigger message by reacting or replying to that message. 
- `Autoroles`: Automatically assign roles upon joining the server. 
- `setmodlogs`: Setup your modlogs channel to get all member logs.
- `setmuterole`: Setup a mute role for your server, and Elyana will automatically fix the role permissions in channels.
- `setquarantinerole`: Setup a quarantine role for your server, and Elyana will automatically fix the role permissions in channels.
- `togglecommand`: Enables/disables a command in your server.
- `setprefix`: Change the bot prefix in your server.
- `Word`: Blacklists/whitelists a word in your server, if `antiprofanity` system in on.
- `channel`: Blacklists/whitelists a channel in your server, if `antiadvertising` system in on.
- `link`: Blacklists/whitelists a link in your server, if `antilinks` system in on.

### Moderation commands:
- `linklist`: Lists all blacklisted links in your server.
- `wordlist`: Lists all blacklisted words in your server.
- `mute`: Mutes a member for x time in your server.
- `unmute`: Removes a member from mute role.
- `quarantine`: Quarantine a member and sends them back to portal.
- `unquarantine`: Remove a member from quarantine role.
- `settings`: List the server configuration settings of the bot.
- `warn`: Warn a member.
- `unwarn`: Revoke a warn from a member.
- `warns`: Lists all the warns of a member.
- `timeout`: Times out a member.
- `kick`: Kicks out a member from the server.
- `ban`: Bans a member from the server

### Apps commands:
Apps commands are the ones you get when you right-click on a user name in the server or on a message sent.
- `flag`: Flagging a message is an open command for members, to flag a message that is considered bad or contains profanity/sexual/racist content.
Flagging a message will send a log to the logs channel and auto react on the message, if it hits 5 reactions it will be automatically deleted.
- `warn/mute/quarantine`: You can warn/quarantine/mute a member fast by right-clicking on a user name or avatar.

### To-do list:
- Adding a channel list command to list all channels where anti-advertising is enabled.
- Mass ban command to use in case of raids.
- Anti-raid system that secures your server in case of raidings.
