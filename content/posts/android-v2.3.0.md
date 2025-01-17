---
title: 'Jellyfin Android v2.3.0 - Improved Integrated Player'
subtitle: 'Enjoy a more polished Jellyfin experience on your phone'
author: 'Max Rumpf'
githubusername: 'Maxr1998'
date: 2021-08-01T00:00:00-00:00
justify: 'center'
---

After a prolonged beta testing period, we're excited to announce that version 2.3.0 of the Jellyfin Android app is now available!

<!--more-->

A lot things have changed since the last stable release, mainly to improve stability and compatibility with the Jellyfin Server.

Communication between the Android app and the server was updated to use [a new library](https://github.com/jellyfin/jellyfin-sdk-kotlin) that supports more modern technologies which improves the development process and allows us to support additional features in the future, eventually resulting in a fully native app that's specifically optimized for phones.

Due to the library changes, the new version of the app **only supports servers of version 10.7.0 or later**, so make sure your server is up-to-date before you install the update!

### Integrated Video Player Improvements

The integrated/native video player was especially reworked and supports playlists now (so that you can binge-watch your shows more easily), allows setting the playback speed and introduced an option in the client settings to remember the screen brightness applied through gestures.

<img alt="Playback speed controls" src="/images/posts/android-v2.3.0/exoplayer-speed-controls.png" />

The Picture-in-Picture (PiP) mode now respects the aspect ratio of your media and will have smooth animations when entering it.
Soon, you'll also be able to select a bitrate limit to force transcoded streaming and reduce data usage, so please look forward to the next updates!

## Polishing and Bug Fixes

You can now set the location to download content to in the client settings.
There were also a lot of bug fixes which will improve the experience with the app, not only in the native player but also for Android Auto support and when casting media to Chromecast.

## Download Now

<a class="NoLinkLook" href="https://play.google.com/store/apps/details?id=org.jellyfin.mobile">
  <img width="153" alt="Jellyfin on Google Play" src="/images/store-icons/google-play.png" />
</a>

<a class="NoLinkLook" href="https://www.amazon.com/gp/product/B081RFTTQ9">
  <img width="153" alt="Jellyfin on Amazon App Store" src="/images/store-icons/amazon.png" />
</a>

<a class="NoLinkLook" href="https://f-droid.org/en/packages/org.jellyfin.mobile/">
  <img width="153" alt="Jellyfin on F-Droid" src="/images/store-icons/fdroid.png" />
</a>

Direct downloads are always available from [our repository](https://repo.jellyfin.org/releases/client/android/).

## Full Release Notes

The full (technical) release notes are available on [GitHub](https://github.com/jellyfin/jellyfin-android/releases/tag/v2.3.0).

## Contributors

As always, lots of great people contributed in this release:

### Jellyfin Team

- [@nielsvanvelzen](https://github.com/nielsvanvelzen) - [Sponsor](https://github.com/sponsors/nielsvanvelzen)
- [@Maxr1998](https://github.com/Maxr1998) - [Sponsor](https://github.com/sponsors/Maxr1998)
- [@h1dden-da3m0n](https://github.com/h1dden-da3m0n) - *Special shout-out for helping with the migration to GitHub Actions!*
- [@ferferga](https://github.com/ferferga) - [Sponsor](https://github.com/sponsors/ferferga)

### Others

- [@CarlosOlivo](https://github.com/CarlosOlivo)
- [@fedesenmartin](https://github.com/fedesenmartin)
- [@ThreeFive-O](https://github.com/ThreeFive-O)
- [@Codex-](https://github.com/Codex-)
- [@diederikdehaas](https://github.com/diederikdehaas)

### Contribute

If you have some experience with Android development and are interested in contributing yourself, feel free to dive into the source code [on GitHub](https://github.com/jellyfin/jellyfin-android) and open pull requests!

Alternatively, you can help translating the app into your language on our [Weblate](https://translate.jellyfin.org/projects/jellyfin-android/jellyfin-android/).

