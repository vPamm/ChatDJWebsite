---
weight: 2
title: "FAQ"
description: "Frequently Asked Questions"
icon: "question_mark"
date: "2025-07-25T08:21:49-04:00"
lastmod: "2025-07-25T08:21:49-04:00"
draft: false
toc: true
---

### Why does this exist?

- [My friend](https://twitch.tv/nikkistoozippy) was streaming on Twitch one day, and I wanted her to swap playlists, and saw she had to manually do it. So I wanted to create something that will add the functionality of [Songify](https://github.com/songify-rocks/Songify), and the swapping of the playlists, plus anything else we could think of tbh.

### Why can't I use the Twitch redemptions I already set up through the dashboard?

- Good question! Ask the Twitch developers. From [their documentation](https://dev.twitch.tv/docs/api/reference/#update-redemption-status), it only says "The app used to create the reward is the only app that may update the redemption." I miss pubsub.

### Why doesn't when I refuse a redemption from the queue, it doesn't remove it from the queue, why do we have to skip it?

- Another great question! Because the Spotify dev's haven't yet (or [won't](https://community.spotify.com/t5/Spotify-for-Developers/API-Delete-Remove-songs-from-queue/td-p/4956378)) implemented that into the API. But c'mon. A multi-billion dollar corporation not doing something to help their community? [Where have I heard that before?](https://community.spotify.com/t5/Spotify-for-Developers/Access-to-websockets/td-p/4955299/)