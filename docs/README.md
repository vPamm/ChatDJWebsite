<!-- docs/README.md -->

# ChatDJ

> A Twitch bot for managing Spotify playlists and handling song requests via channel point redemptions on Twitch.


## Features

- **Swap Playlists**: Use a channel point redemption to cycle through multiple predefined Spotify playlists.
- **Song Requests**: Let viewers request songs by submitting Spotify links via channel point redemptions.
- **Community Playlists**: Have your viewers build a playlist with you!

## Prerequisites

* Go (v1.16 or higher)
* A Twitch Affilate/Partner Account (For channel point redemptions)
* A Spotify Premium Account
* A Twitch Application (https://dev.twitch.tv)
  - With a redirect url of http://localhost:5000/api/auth/twitch/callback
* A Spotify Application (https://dev.spotify.com)
  - With a redirect url of http://localhost:5000/api/auth/spotify/callback
  - Also using the Web API and the Web Playback SDK

## Commands

- !queue - Will list the current queue.
- !playlist - Will list the community playlist setup in the settings.
- !skip - Will start a vote to skip the current song.
- !forceskip - Will forcefully skip to the next song. (Mod Only.)

## Demo

![Demo GIF](https://i.imgur.com/Ls2ktg7.gif)