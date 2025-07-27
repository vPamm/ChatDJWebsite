---
weight: 1
title: "Overview"
description: "What's this all about?"
icon: "overview"
date: "2025-07-25T13:01:54-04:00"
lastmod: "2025-07-25T13:01:54-04:00"
draft: false
toc: true
---

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
* A [Twitch Application](docs/getting-started/setup-applications/twitch)
* A [Spotify Application](docs/getting-started/setup-applications/spotify)

## Commands

- !queue - Will list the current queue.
- !playlist - Will list the community playlist setup in the settings.
- !skip - Will start a vote to skip the current song.
- !forceskip - Will forcefully skip to the next song. (Mod Only.)

## Demo

![Demo GIF](/images/demo.webp)