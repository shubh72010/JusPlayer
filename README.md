# JusPlayer

![The app screenshot]([./images/browse_home.png](https://media.discordapp.net/attachments/1387711977794572303/1486687886613938476/image.png?ex=69c6697d&is=69c517fd&hm=dc44a4bb03c246fd7fb393c998e7a5c6b7c73270ed834eb748d44e085ed5c337&=&format=webp&quality=lossless&width=1323&height=747))

![The app screenshot]([[./images/browse_home.png](https://media.discordapp.net/attachments/1387711977794572303/1486687886613938476/image.png?ex=69c6697d&is=69c517fd&hm=dc44a4bb03c246fd7fb393c998e7a5c6b7c73270ed834eb748d44e085ed5c337&=&format=webp&quality=lossless&width=1323&height=747)](https://media.discordapp.net/attachments/1387711977794572303/1486687990691397672/image.png?ex=69c66996&is=69c51816&hm=3090c3cd16fa23da9013b8a9b1a4013ad6e45240a69c97ff6c486a39e676e806&=&format=webp&quality=lossless&width=943&height=531))

**JusPlayer** is a free and open-source advanced media player for Android TVs and TV boxes, built by [JusDots](https://shubh72010.github.io/JusDots-Devs)). It allows you to play content from various public sources — completely ad-free, with no compromises.

### ✅ Features
- No ads
- SponsorBlock integration
- Adjustable playback speed
- 8K resolution support
- 60fps playback
- HDR compatibility
- Live chat support
- Customizable buttons
- Does not require Google Services
- Helpful international community

### ❌ Limitations
- Not supported on phones and tablets
- Comment functionality is unstable
- Voice search and casting performance may be inferior to official apps, depending on your device

Give it a try!

**Have a question?** Ctrl+F or ⌘F this readme first!

[**Installation**](#installation) | [**Official Site**](https://jusdots.com) | [**FAQ**](#faq) | [Support / Chat](#support) | [Build](#build) | [Changelog](https://github.com/jusdots/JusPlayer/releases)

---

## Device support

> [!IMPORTANT]
> Starting in October 2025, new Amazon FireTV devices no longer run Android under the hood. JusPlayer will **not** be compatible with the Fire Stick 4K Select and newer devices which run Amazon's own VegaOS.

![Device support image](images/new/compatibility.png)

- **Supported:** All Android TVs and TV boxes (incl. all FireTV devices released before Oct. 2025, NVIDIA Shield & Chromecast with Google TV), even older ones running Android 4.3 (KitKat).
- **Not supported:** Smartphones, non-Android platforms like Samsung Tizen, LG webOS, Apple TV, etc.

---

## Installation

**Do not** download JusPlayer from any **app store**, APK websites or blogs — these may have been uploaded by third parties and could contain malware or ads. JusPlayer is not officially published on any app store.

There is a **beta release** (recommended) and a **stable release**. Beta gets new features and bugfixes faster than the stable release.

You can use any of the following methods to install:

- (**Easiest**) Install [Downloader by AFTVnews](https://www.aftvnews.com/downloader/) on your Android TV, open it, and enter the JusPlayer download URL. Read, understand, and confirm the security prompts.
- Install a file transfer app on your Android TV, download the APK on your phone or computer, and transfer it to your TV (e.g. [_Send Files to TV_](https://sendfilestotv.app/)).
- Download the APK onto a USB stick, plug it into your TV, and use a file manager (e.g. [_FX File Explorer_](https://play.google.com/store/apps/details?id=nextapp.fx) or [_X-plore_](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore)). Android's preinstalled file manager does not work.
- Advanced users can install via ADB. [guide](https://fossbytes.com/side-load-apps-android-tv/#h-how-to-sideload-apps-on-your-android-tv-using-adb)

**Troubleshooting:** If installation fails, your **disk space may be full** or the APK didn't download correctly. If the app crashes on launch, make sure it's installed to internal memory — not an SD card or external storage.

**JusPlayer has a built-in updater** with a changelog. All releases are also available on [GitHub](https://github.com/jusdots/JusPlayer/releases).

> Latest [**beta download**](https://github.com/jusdots/JusPlayer/releases/download/latest/jusplayer_beta.apk)
>
> Latest [**stable download**](https://github.com/jusdots/JusPlayer/releases/download/latest/jusplayer_stable.apk)


### Installation (Chromecast with Google TV)

On **Chromecast with Google TV**, installation of apps is blocked by default. An extra step is required:

> **1. Enable Developer Options**
>
> Go to _Settings > System > About_. Scroll to _Android TV OS build_ and click it repeatedly until you see the developer options toast message.
>
> **2. Turn on the "unknown sources" setting**
>
> Go back to main _Settings_ → _Apps > Security & Restrictions > Unknown sources_. Enable it for whichever installer you plan to use.
>
> [[source & picture guide](https://www.androidpolice.com/2021/02/07/how-to-sideload-any-apk-on-the-chromecast-with-android-tv/#install-the-apk)]

After this, follow the [general installation guide](#installation) above.


### Installation (Xiaomi devices with Chinese firmware)

Xiaomi's **Chinese firmware** may block installation of the **beta version**. International firmware is not affected. Solutions:

1. Use JusPlayer's **stable version** instead (**recommended**)
2. Switch to international firmware for your device
3. (2020 devices or older) Factory reset, install JusPlayer beta before any system updates, then update safely


### Updating

JusPlayer has a built-in updater. You only need to follow the installation procedure **once**. A few seconds after launch, it will notify you of any available update along with a changelog. You can disable automatic update checks or manually check under _Settings > About > Check for updates_.

---

## Compatibility

JusPlayer requires Android 4.3 or above. It does not work on non-Android devices (incl. LG or Samsung TVs). On unsupported TVs, a TV stick or TV box is recommended.

Tested successfully on:

- Android TVs & Google TVs (e.g. Philips, Sony)
- Chromecast with Google TV & TVs with _Chromecast built-in_
- Amazon FireTV stick (all generations)
- NVIDIA Shield
- Android TV boxes (including budget/no-name devices)
- Xiaomi Mi Box

---

## Features

### Adblocking

JusPlayer does not show any ad banners, preroll ads, or ad intermissions. It is literally programmed to be completely **unable** to display ads — YouTube cannot inject anything in. This also means you cannot whitelist channels for ads. Sponsored segments within videos can be skipped via SponsorBlock (see below).


### SponsorBlock

JusPlayer includes SponsorBlock integration. From the [SponsorBlock website](https://sponsor.ajay.app/):

> SponsorBlock is an open-source crowdsourced browser extension and open API for **skipping sponsor segments** in YouTube videos. The extension automatically skips sponsors it knows about using a privacy-preserving query system. It also supports skipping other categories such as intros, outros, reminders to subscribe, and non-music parts in music videos.

You can select which categories to skip in settings. Note that SponsorBlock is a community-driven project — coverage is not guaranteed for every video.


### Casting

To cast videos from your phone (or other device), you must link it to your TV first. Unlike the official YouTube app, JusPlayer does not automatically appear when on the same WiFi network. To link:

1. Open JusPlayer → _Settings_
2. Go to **"Remote control"**
3. On your phone's YouTube app → _Settings > General > Watch on TV_
4. Tap _Connect using TV code_ and enter the code shown on your TV

[**Screenshot guide**](https://t.me/SmartTubeEN/8514)

> **Note:** Due to technical limitations, the app must be open on your TV before casting. JusPlayer cannot automatically wake the TV.


### Picture-in-Picture (PiP)

JusPlayer supports PiP mode. Enable under _Settings > General > Background playback > Picture in picture_. The video enters PiP when you press Home during playback, or Back (if configured).


### Adjust Speed

Tap the speed indicator icon (gauge) in the top row of the player to adjust playback speed. Your preference is remembered across videos. Some speed settings may cause frame drops — this is a known limitation.


### Voice Search

To enable global voice search, an additional bridge app must be installed alongside JusPlayer. This bridge intercepts the system's attempts to open the official YouTube app and redirects to JusPlayer instead. The official YouTube app must be uninstalled for this to work.

**On Amazon Fire TV:**
1. Uninstall the official YouTube app (no root required)
2. Download and install the Amazon Bridge app from the JusPlayer GitHub releases page

**On Google Chromecast with Google TV:**
1. Uninstall the official YouTube app (no root required)
2. Download and install the ATV Bridge app from the JusPlayer GitHub releases page

**On all other Android devices** (root required):
1. Root your device
2. Uninstall official YouTube: `adb shell pm uninstall com.google.android.youtube.tv`
3. Install the ATV Bridge app from the JusPlayer GitHub releases page

---

## Support

**Please check the [FAQ](#faq) first!**

You can report bugs or request features via the [issue tracker on GitHub](https://github.com/jusdots/JusPlayer/issues).

- **Discord**: [JusDots Official](https://discord.gg/jusdots)
- **GitHub**: [github.com/jusdots/JusPlayer](https://github.com/jusdots/JusPlayer)

---

## Team

JusPlayer is a product of [**JusDots**](https://jusdots.com), a tech startup building hardware and software that respects users. The core team includes:

- **Flakious** — CEO & Founder
- **Dikshant** — COO
- **Karan** — CDO
- **Youvaan** — Co-Founder & Frontend
- Plus contributors from the broader JusDots community

Several community members have also helped with translations and testing. Contributions are welcome on [GitHub](https://github.com/jusdots/JusPlayer).

---

## Build

> **NOTE: OpenJDK 14 or older (!) is required. Newer JDK may cause crashes.**

```bash
git clone https://github.com/jusdots/JusPlayer.git
cd JusPlayer
git submodule update --init
adb connect <device_ip_address>
gradlew clean installJusplayerStableDebug
```

---

## Video Codecs

Video codecs are the algorithms used for video compression.

### Which codec to choose

|          | Recommendation                               | Hardware support             | Compression / bitrate              | Quality |
|:--------:|:---------------------------------------------|:-----------------------------|:----------------------------------:|:-------:|
| **AV01** aka AV1 | Best choice, **if your device supports it** | Devices from **2020+** | **Best** *(e.g. 1.6 Mbps)* | Same |
| **VP9**  | **Best choice on most devices**              | Most devices **since 2015** | **Better** *(e.g. 2.1 Mbps)* | Same |
| AVC      | Only for old or slow hardware               | **All** devices              | Good *(e.g. 2.7 Mbps)* | Same |

At the same resolution, **lower bitrate is better.** YouTube targets the same quality regardless of codec. Older codecs have a higher bitrate because they're less efficient — this is a flaw, not a feature. Use the newest codec your device can handle smoothly.

### Which quality to choose?

Configure a default video preset under _Settings > Video Player > Video Presets_. "None" remembers your last manual selection. Consider:

- Your bandwidth (test at [fast.com](https://fast.com))
- Your TV's display resolution
- Your TV's HDR and 60fps capabilities

### HDR

HDR works only **if your hardware supports it**:

- Your TV must support HDR
- If using a TV box, the box, cable, **and** TV must all support it
- The NVIDIA Shield generally supports HDR, but **not** the specific HDR format used on YouTube

If HDR looks dim or washed out, [this article](https://www.wired.com/story/hdr-too-dark-how-to-fix-it/) may help.

---

## Liability

JusDots takes no responsibility for how JusPlayer is used, or external instances provided by third parties. We strongly recommend you abide by all applicable laws in your country. We refuse liability for any inappropriate use of this software, such as illegal downloading.

You may view the LICENSE [here](./LICENSE).

> IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM.

---

## FAQ

### Q: Videos buffer a lot

A: Try switching to an encrypted DNS like NextDNS. You can configure it automatically using [Intra (F-Droid)](https://f-droid.org/en/packages/app.intra/) with AutoStart for persistence. For manual setup, [use this guide](https://www.reddit.com/r/MiBox/s/7esEVGtAAa).

### Q: No search results when using voice search (Android 11)

A: A recent update to "Google app for Android TV" may cause this. Deleting the update should fix it.

### Q: AV01 doesn't play / VP9 is slow on my device

A: Most TVs and TV boxes do **not** have hardware support for AV01. Without it, the codec cannot play at all. VP9 at high resolutions may also be slow on budget devices without 4K hardware support.

### Q: Can JusPlayer look like the official YouTube app?

A: Not currently. JusPlayer follows Google's official Android TV UI template. Reworking the UI requires dedicated long-term effort — contributions are welcome.

### Q: Can I install this on a Samsung Tizen / LG webOS / Roku / iOS device?

A: No. JusPlayer works only on **Android** devices. For non-Android TVs, use a separate Android TV stick or box.

### Q: Can I install this on a smartphone?

A: This app is **not** designed for smartphones and we offer **zero support** for it on phones. You can cast **from** your phone to a TV running JusPlayer though. For a phone YouTube client, see [ReVanced](https://github.com/ReVanced) or [NewPipe](https://newpipe.schabi.org).

### Q: I get "unknown codec" / "can't download video" errors

A: Wait 5 seconds for the video to load, then press Play. This can also occur with a USB audio device attached or when disk storage is full.

### Q: I get "the video profile is not supported"

A: Press the HQ button in the bottom-left, select _Video Formats_, and switch from AV01 to VP9. See [Video Codecs](#video-codecs) for more.

### Q: I get "Sign in to confirm you're not a bot"

A: Your IP address range may be temporarily or permanently blocked by YouTube when not signed in. Signing in to your account should resolve this.

### Q: The video is buffering a lot

A: Try one or more of the following:
- Reduce the resolution or change the video format to AVC
- Increase the buffer size in settings
- Press back and replay the video

### Q: Why does it skip video segments?

A: That's **SponsorBlock** working as intended. You can configure or disable it in settings. See [SponsorBlock](#sponsorblock) for details.

### Q: How do I enable autoplay / stop after each video?

A: Use the loop button 🔁 in the player to cycle between autoplay modes.

### Q: Can I download videos?

A: No, video downloading is not supported.

### Q: Can updates install automatically?

A: No — only the system's preinstalled package manager has that permission. JusPlayer will prompt you when an update is available; you confirm and install from there.

### Q: Can I whitelist ads on specific channels?

A: No. JusPlayer has no ad-display code at all. Adding this functionality would require deliberate effort — which is instead spent on useful features and bugfixes.

### Q: What is AFR?

A: Auto Frame Rate. It adjusts your TV's refresh rate to match the content. The improvement is subtle; most people don't notice it. **Recommendation:** Turn it on and test — if it causes issues, turn it off.

### Q: Should I use high or low buffer?

A: **High**. A higher buffer smooths out network hiccups and prevents mid-video pauses. The RAM overhead is negligible.
