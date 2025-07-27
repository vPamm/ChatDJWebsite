---
weight: 7
title: "Spotify"
description: "Setting up the Spotify side of things"
icon: "settings"
date: "2025-07-25T09:21:36-04:00"
lastmod: "2025-07-25T09:21:36-04:00"
draft: false
toc: true
---

## Setting up the Application

- Go to the [Spotify Dev Dashboard.](https://dev.spotify.com)
- Create a new application.
- Make your settings look like [this.](/images/spotify.png)

### Settings required

{{< table "table-hover" >}}

| Setting | Value |
|-----|----|
| `App Name` | ChatDJ (or whatever else you want to name it)
| `App description` | really doesnt matter what you put in here
| `Redirect URIs` | http://localhost:5000/api/auth/spotify/callback
| `APIs used` |  Web API and Web Playback SDK
{{< /table >}}

- Input your client ID and secret from the dashboard [into the program.](/images/spotify_settings.png)
- Save the settings.
- Login to Spotify.