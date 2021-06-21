# Bonk

Bonk is a Discord bot developed using Discord.js, it features osu! related functionalities.

## Currently implemented

### Commands

- Fully-fledged **user** command, used to display an osu! player profile card in the form of a Discord embed.
- **osuset** command, used to assign a osu! user id to a discord user, in order to simplify per-user osu! commands.
- **ping** command, used for checking if the bot's online.
- **prefixset** command, used to change the prefix used to trigger commands (unique for each server).
- **shutdown** command, used to force restart the bot.
- **status** command, used to update the bot's status.
- ... and more to come! (see the To-do list)

## To-do

### Structure

- [ ] Allow per-server command enabling/disabling
- [ ] Allow per-channel command enabling/disabling
- [ ] Two display modes: canvas and embed

### Commands

- [ ] Roll
- [ ] Retrieving a user's most recent score (!recent)
- [ ] Displaying beatmap data (!beatmap)
  - [ ] Basic features
  - [ ] pp calc features
  - [ ] beatmap snapshots using canvas
  - [ ] dynamic map preview
- [ ] Displaying a user's top plays
  - ...
- [x] Displaying a user's "playing profile" (!user)
- [ ] Displaying a user's "mapping profile"
  - ...
- [ ] Displaying replay data
  - [ ] Rendering the whole replay in itself
  - [ ] Allow choke point analysis
- [ ] Random map recommandation, including filters for skillsets and difficulty range (std)
- [ ] BWS calculations for tournament players (+formula customization)
- [ ] Multiplayer matches analysis
  - [ ] For tournament matches (match costs with advanced features)
  - [ ] For casual lobbies (player stats)
- [ ] o!mm (Maid Bot) API integration (?)
- [ ] Playing session reports (by user)

### Channel alerts ("Widgets")

- [ ] Hourly global leaderboard
  - [x] Job
  - [x] Fetching
  - [ ] Fully-fledged integration
- [ ] New scores (filters: min pp, user, country)
  - [ ] Job
  - [ ] Fetching
  - [ ] Fully-fledged integration
- [ ] New beatmaps (filters: all, by mapper, by diff range, by status)
  - [ ] Job
  - [ ] Fetching
  - [ ] Fully-fledged integration
- ...

### Code commenting

- [x] index.js
- [x] commands
- [ ] jobs
- [ ] functions