# Sandpit Turtle Karaoke

A synchronised lyrics display for home karaoke parties. Search for a YouTube video, pick a track from [lrclib.net](https://lrclib.net), and the lyrics scroll in time with the music.

## Setup

Create a `config.js` in the project root (not tracked by git):

```js
const YT_API_KEY = 'your_youtube_data_api_v3_key_here';
```

Get a key at [Google Cloud Console](https://console.cloud.google.com/) → APIs & Services → YouTube Data API v3. Restrict it to your domain for safety.
