# Minecraft Community Discord Bot

A Discord.js v14 bot for Minecraft community servers with setup, tickets, moderation and anti-raid controls.

## Deploy
1. Create a Discord application at https://discord.com/developers/applications and add a bot.
2. Enable **Server Members Intent** in Bot settings.
3. Invite it using OAuth2 URL Generator with `bot` and `applications.commands` scopes and suitable permissions.
4. Deploy this repository as a Node.js worker. Set `TOKEN`, `CLIENT_ID`, and `GUILD_ID` as environment variables.
5. Run `/setup minecraft` in your server as an administrator.

Never commit your real token. SQLite data may be lost on hosts without persistent storage. Review permissions and test moderation commands before using in a live server.

Commands include `/setup minecraft`, `/ticket panel`, `/warn`, `/warnings`, `/kick`, `/timeout`, `/ban`, `/softban`, `/unban`, `/lockdown`, and `/antiraid`.
