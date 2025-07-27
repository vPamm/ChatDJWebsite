---
weight: 6
title: "Twitch"
description: "Setting up the Twitch side of things"
icon: "settings"
date: "2025-07-25T09:02:42-04:00"
lastmod: "2025-07-25T09:02:42-04:00"
draft: false
toc: true
---

## Setting up the Application

- Go to the [Twitch Dev Dashboard.](https://dev.twitch.tv)
- Create an application (not an extension.) [Example](/images/application.png)
- Make the settings look like [this.](/images/twitch.png)

### Settings required

{{< table "table-hover table-sm" >}}

| Setting | Value |
|-----|----|
| `Name` | ChatDJ
| `OAuth Redirect URLs` | http://localhost:5000/api/auth/twitch/callback
| `Category` | Website Integration
| `Client Type` | Confidential |
{{< /table >}}

- Input your client ID and secret from the dashboard into the program.
- Save the settings.
- Login to Twitch.

## Setting up Channel Point Redemptions

*This is due to how Twitch sets up Channel Point Redemptions via the API, if you create it via the dashboard, you can't use it in the API. See [here](https://discuss.dev.twitch.com/t/bug-update-custom-reward-redemption-gives-403/61230/4)*


- Make sure you don't already have a "Song Request", "Swap Playlists", or "Add to Playlist" redemption, if you do, delete them.
- Also make sure you've setup your Twitch settings and logged in.
- Enter your Redemption details [here.](/images/redemptions.png)

### Settings required

{{< table "table-hover table-sm" >}}

| Setting | Value | Required By
|-----|----|----|
| `Title` | {name of the redemption} | Song Request, Swap Playlist, Add to Playlist
| `Cost` | {cost of the redemption} | Song Request, Swap Playlist, Add to Playlist
| `Prompt` | {the description of the redemption} | Song Request, Swap Playlist, Add to Playlist
| `Playlist Link` | {URL to the spotify playlist} | Add to Playlist

{{< /table >}}

- Click "Create Reward"
