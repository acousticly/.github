# Changelog
All notable changes to this project will be documented in this file.
## [0.9.7](https://docs.acoustic.to/blog/2022/01/08/january-update) (Music) - 2021-01-08
### Added:

#### Favorites are coming to Acoustic:

This introduces an improved way to listen to your favorite songs!

![favorites button on player start](https://cdn.jevestobs.dev/1641678626.png)

#### You can easily view your favorites using the `~favorites` command

![Viewing your favorites](https://cdn.jevestobs.dev/1641679616.png)

<br />

#### `Play` command gets **autocomplete** ✨

Do you hate typing out the exact song you want? With autocomplete, you can find your song in on average **6 characters or fewer** 🤯

<br />

![Autcomplete in action](https://cdn.jevestobs.dev/1641680364.png)

### Changed:

- Lowered cooldowns on all commands
- Greatly improved Spotify song searching
- Switched search engine from YouTube Music to YouTube
- Added custom id's to every playlists for upcoming features 👀
- Some minor tweaks to the UI
- Flow for creating playlists is easier now
- Added a quick link to the support server when a command errors
- Improved lyrics searching
- Use Spotify's API for song info when playing a song/playlist from Spotify

### Fixed:

- Fixed readable time being null on Apple Music fetch
- Fix command replies for `playnext` `pause` `resume` & `shuffeplay`
- Fixed a bug where searching would allow you to add more songs to your custom playlist without premium
- Fixed Twitch tracks not working after a `voiceStateUpdate`

### Server Changes:

##### Berk was kind enough to design us a new banner, and I must say it looks amazing

Go check out [his server](https://discord.gg/sharecodes) if you want to support him for helping us out. 😊

![Server changes](https://cdn.discordapp.com/attachments/832707005780459551/929196376393408512/Acoustic_banner_1_3.png)
