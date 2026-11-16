# PullClip Bookmarklet

A one-click bookmarklet for [PullClip](https://pullclipvid.com/), a free online video downloader. Click it on any video page and the same video opens in PullClip, ready to save as MP4 or MP3.

## Install

1. Show your bookmarks bar (Ctrl+Shift+B on Windows and Linux, Cmd+Shift+B on Mac).
2. Create a new bookmark and name it **PullClip it**.
3. Paste the code below as the bookmark's URL.

```javascript
javascript:(function(){location.href='https://pullclipvid.com/?url='+encodeURIComponent(location.href)})();
```

You can also drag the **PullClip it** button from the [PullClip homepage](https://pullclipvid.com/) straight to your bookmarks bar.

## How it works

The bookmarklet takes the address of the page you are on and opens `https://pullclipvid.com/?url=...` with it. Nothing else runs on the page, nothing is installed, and it needs no permissions.

## What PullClip supports

PullClip saves public videos from 28 sites, including:

- [YouTube](https://pullclipvid.com/youtube-video-downloader/), [TikTok](https://pullclipvid.com/tiktok-downloader/), [Instagram](https://pullclipvid.com/instagram-downloader/), [Facebook](https://pullclipvid.com/facebook-video-downloader/), [X (Twitter)](https://pullclipvid.com/twitter-video-downloader/) and [Pinterest](https://pullclipvid.com/pinterest-video-downloader/)
- [VK](https://pullclipvid.com/vk-video-downloader/), [OK.ru](https://pullclipvid.com/okru-video-downloader/), [Rutube](https://pullclipvid.com/rutube-video-downloader/), [Bilibili](https://pullclipvid.com/bilibili-video-downloader/), [Vimeo](https://pullclipvid.com/vimeo-video-downloader/) and [Kick](https://pullclipvid.com/kick-clip-downloader/)

Choose MP4 from 144p up to 1080p, or MP3 for the audio. You can trim a clip before saving or save a single frame as an image. No account and no app needed.

PullClip only downloads public videos. Please respect the rights of creators and each platform's terms.

## Other languages

- Español: [Descargar videos](https://pullclipvid.com/es/)
- Português: [Baixar vídeos](https://pullclipvid.com/pt/)
- Русский: [Скачать видео с ВК](https://pullclipvid.com/skachat-video-s-vk/)
