# Make YouTube Live Streams Look More Like Twitch

Even if you do not intend to watch in Theater Mode, the YouTube Livestreams Theater Mode extension is recommended for watching YouTube live streams. It adds quite a few useful options, including defaulting the chat to Live chat instead of Top chat and adding colors to usernames to make them easier to tell apart.

## Instructions

1. Install the YouTube Livestreams Theater Mode extension:
    - [Chrome](https://chromewebstore.google.com/detail/youtube-livestreams-theat/cmjhejfkhdonjimgkinjdombabgfbcal)
    - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/youtubelivestreamstheatermode/)

2. After installing the extension, make sure to click on it and go to the options; suggested settings shown below:

## Settings

### Settings Review

For a detailed review of the settings and their impact, you can refer to this link:

![Settings Review](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/settings_preview.png)

*After setup preview:*

![Settings Preview](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/after_setup_preview.png)

## Fix Buffering/Latency Issues

In general, YouTube does not prioritize keeping live stream latency as low as Twitch does. If you hover over the video and see that the LIVE indicator next to the volume slider is grayed out, the video has fallen behind the live stream.

The YouTube Live Stream Latency Mitigator extension will fast forward YouTube live streams in order to catch up with the live stream when you fall behind (similar to the default behavior of Twitch).

## Instructions

1. Install the YouTube Live Stream Latency Mitigator extension:
    - [Chrome](https://chromewebstore.google.com/detail/youtube-live-stream-laten/ambdnabnehojedeaffciphbmfhfmfmjp?hl=en)
    - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/youtube-live-stream-laten/)

2. Optionally, configure the extension by clicking on it as shown below:

*Preview:*

![Latency Mitigator Preview](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/mitigator_preview.png)

## Enable Hardware Video Decoding With Firefox and AMD GPUs

If you are using Firefox with an AMD GPU, hardware video decoding is most likely disabled by default. To enable it, change `media.hardware-video-decoding.force-enabled` to `true` in `about:config`.

## Instructions

1. Navigate to `about:config`.
2. Enter `media.hardware-video-decoding.force-enabled` in the search box.
3. Toggle the setting to `true` as shown below:

*Preview:*

![Hardware Video Decoding Preview](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/video_decoding_setting_preview.png)

## YouTube Playback and Performance Settings

If you notice that live streams are buffering a lot and/or have a lot of latency, this may be due to YouTube using the VP9 codec without hardware decoding. If your PC supports AV1 hardware decoding, YouTube should show an option to always use AV1 under the Playback and Performance settings.

## Instructions

1. Navigate to [youtube.com/account_playback](https://youtube.com/account_playback).
2. Select "Always prefer AV1" under AV1 settings as shown below:

*Preview:*

![AV1 Settings Preview](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/youtube_account_playback_preview.png)

## Using enhanced-h264ify Extension

If the above does not work, the easiest way to make YouTube use a different codec is to install the enhanced-h264ify extension.

Please note that by default, the enhanced-h264ify extension disables everything except h264. This can be configured by clicking on the extension after installing it.

## Instructions

1. Install the enhanced-h264ify extension:
    - [Chrome](https://chromewebstore.google.com/detail/enhanced-h264ify/omkfmpieigblcllmkgbflkikinpkodlk?hl=en)
    - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/enhanced-h264ify/)

2. Refresh any already open YouTube streams.

3. Optionally, configure the extension by clicking on it as shown below:

*Preview:*

![Enhanced-h264ify Preview](https://raw.githubusercontent.com/madmaxgrey/better-youtube-live/main/Preview%20Images/enhanced_h264ify_settings_preview.png)