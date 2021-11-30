# Changelog
All notable changes to this project will be documented in this file.
## [0.9.6](https://docs.acoustic.to/blog/2021/11/29/november-update) (Music) - 2021-11-29
### Added:
#### Music has new commands :partying_face:
- `playnext` When you really want to show your friends a funny video that just can't wait. The playnext command moves songs to the front of the queue **without** skipping the currently playing song.
- `shuffleplay` Are you getting tired of hearing the same songs when you queue a playlist on Acoustic? Well no more. Now you can auto-shuffle playlists and queue them instantly! :star_struck:
- `clearqueue` This is a long-awaited command, and it's finally here! It clears the queue **without** disconnecting the bot. How revolutionary and innovative...
#### `Lyrics` command gets a full rework with buttons support
And it looks pretty awesome, if I do say so myself <br>
![Lyrics lookin' dope af](https://cdn.jevestobs.dev/image_50.png)
### Changed:
- Some wording was messed with, and instructions should be clearer
- Song searches should be more accurate on average
- Viewing your custom playlist now prefetches the hyperlinks so you can visualize the playlist's song makeup
- Thumbnail art for Soundcloud 
- Database migration from MongoDB to ScyllaDB (+55% OPS read/write)
- Updated [privacy policy](https://acoustic.to/privacy) and [terms](https://acoustic.to/terms)

### Fixed:
- `skip` command interaction failed
- `ping` command inaccuracies
- `loop` command failure when skipping

## [0.9.6](https://docs.acoustic.to/blog/2021/10/29/october-update) (Economy) - 2021-10-24
### Added:
#### Blackjack now has new gamerules: 
- Double-Down
- Split
- Soft hands (Aces can be 1 or 11)
### Changed:
- Camera shop item buffed
- Mine command now accepts responses from everyone, so somebody can steal your guess
- Mine command now has 4 potential numbers
- Search command UI overhaul
- Blackjack logic/UI completely reworked that finally looks acceptable on mobile
### Fixed:
- Greatly improved global leaderboard accuracy
### Removed:
- Herobrine
