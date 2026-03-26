<p align="center">
  <a href="https://f-droid.org/packages/app.smarttube.fdroid/">
    <img src="https://fdroid.gitlab.io/artwork/badge/get-it-on-en.svg" alt="Get it on F-Droid" width="206" style="max-width:100%; height:auto;"/>
  </a>
</p>

# Important Announcement About the App

My development environment was infected by unknown malicious software. Some builds may have been affected. Once detected, I secured everything via a full disk wipe, restored a clean setup, and now all builds are scanned with VirusTotal. The F-Droid version will also be verified before release.

Public keys may have been compromised. You can download the new version and new public key below. Instructions for restoring backups are provided.

No extra action is required since the app uses **one-time connection codes** with limited permissions (e.g., cannot change your password). Still, you can revoke them for full peace of mind.

### How to Revoke Access:

1. Open [myaccount.google.com/security](https://myaccount.google.com/security)  
2. Find **“Your connections to third-party apps & services”**  
3. Tap **“See all connections”** and locate **YouTube TV** or **Google Drive**  
4. Select the app → **“Remove access”**  

Keep built-in security features enabled for protection.

---

# SmartTube

![App Screenshot](./images/browse_home.png)

SmartTube is a free and open-source advanced media player for Android TVs and TV boxes. It plays content from various public sources.

### ✅ Features
- No ads  
- SponsorBlock integration  
- Adjustable playback speed  
- 8K resolution support  
- 60fps playback  
- HDR compatibility  
- View live chat  
- Customizable buttons  
- Does not require Google Services  
- Helpful international community

### ❌ Limitations
- Not supported on phones and tablets  
- Comment functionality is unstable  
- Voice search and casting may be inferior to official apps depending on the device  

**Do you have a question?** Use Ctrl+F or ⌘F in this README first.

[**Installation**](#installation) | [**Official Site**](https://smarttubeapp.github.io) | [**Donation**](#donation) | [**FAQ**](#faq) | [Support / Chat](#support) | [Build](#build) | [Translate the app](https://jtbrinkmann.de/tools/android-strings.xml-translator.html) | [Changelog](https://t.me/s/SmartTubeNewsEN) | [Liability](#liability)

---

## Device Support

> [!IMPORTANT]  
> Starting October 2025, new Amazon FireTV devices no longer run Android. SmartTube will **not** be compatible with Fire Stick 4k Select and newer VegaOS devices.

![Device support image](images/new/compatibility.png)

* **Supported:** Android TVs and TV boxes (incl. older FireTVs, NVIDIA Shield, Chromecast with Google TV) with Android 4.3+  
* **Not Supported:** Smartphones, non-Android platforms (Samsung Tizen, LG webOS, Apple TV, etc.)

---

## Installation

> [Video Guide](images/new/zPV0imF.mp4) (download URL: `kutt.to/stn_beta` or `kutt.to/stn_stable`)

**Do not** download SmartTube from app stores, APK websites, or blogs; these may contain malware or ads. SmartTube is **not** officially published on any app store.

There is a **beta release** (recommended) and a **stable release**. Beta gets new features and bugfixes faster.

### Methods to Install

1. **Easiest:** Install [Downloader by AFTVnews](https://www.aftvnews.com/downloader/) on your Android TV, open it, and enter `kutt.to/stn_beta` or `kutt.to/stn_stable`. Read and confirm security prompts.  
2. Use a file transfer app to move the APK from your phone/computer to the TV (e.g., [_Send Files to TV_](https://sendfilestotv.app/)).  
3. Use a USB stick: download the APK, insert the stick into your TV, and open it with a file manager app (e.g., [_FX File Explorer_](https://play.google.com/store/apps/details?id=nextapp.fx) or [_X-plore_](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore)). Do **not** use ad-filled file managers like _FileCommander_.  
4. Advanced users: install via ADB. Guides: [Fossbytes](https://fossbytes.com/side-load-apps-android-tv/#h-how-to-sideload-apps-on-your-android-tv-using-adb) | [AFTVnews](https://www.aftvnews.com/sideload/)  

**Troubleshooting:** If installation fails, check disk space or re-download APK. Install to internal memory, not SD/external storage. The app has a built-in updater with changelog.

> Latest beta: [smarttube_beta.apk](https://github.com/yuliskov/SmartTube/releases/download/latest/smarttube_beta.apk)  
> Latest stable: [smarttube_stable.apk](https://github.com/yuliskov/SmartTube/releases/download/latest/smarttube_stable.apk)

---

## Compatibility

Requires Android 4.3+; unsupported on non-Android TVs. While technically runs on phones/tablets, it's **not optimized** and has no official support.

Tested on:
- Android TVs & Google TVs (Philips, Sony)  
- Chromecast with Google TV & TVs with Chromecast built-in  
- Amazon FireTV sticks (all generations)  
- NVIDIA Shield  
- Android TV boxes (including cheap Chinese models)  
- Xiaomi Mi Box  

---

## Features

### Adblocking
- No ads, preroll, or intermissions. Fully prevents YouTube from inserting ads. No whitelist possible.

### SponsorBlock
- Skips sponsors automatically using crowdsourced database.  
- Supports other categories: intros, outros, reminders, non-music segments.  
- Cannot submit new segments from SmartTube (TV remotes are imprecise).  

### Casting
1. Open SmartTube → Settings → Remote control  
2. On your phone, open YouTube → Settings → General → Watch on TV  
3. Connect using TV-code from SmartTube  

**Note:** TV must be on before casting.

### Picture-in-Picture (PiP)
- Enable under _Settings > General > Background playback > Picture in picture_.  

### Adjust Speed
- Tap speed indicator in the player. Remembered across videos. Frame drops possible at high speeds.

### Voice Search
- Requires bridge app and uninstalling original YouTube app.  
- Amazon Fire TV: [Bridge](https://kutt.to/stn_bridge_amazon)  
- Chromecast: [Bridge](https://kutt.to/stn_bridge_atv)  
- Other Android devices: root required + install ATV Bridge.

---

## Donation

Support development:
- [Patreon](https://www.patreon.com/smarttube)  
- PayPal: firsth<!-- abc@def -->ash@gmai<!-- @abc.com -->l.com  
- BTC: 1JAT5VVWarVBkpVbNDn8UA8HXNdrukuBSx  
- LTC: ltc1qgc24eq9jl9cq78qnd5jpqhemkajg9vudwyd8pw  
- ETH: 0xe455E21a085ae195a097cd4F456051A9916A5064  
- ETC: 0x209eCd33Fa61fA92167595eB3Aea92EE1905c815  
- TRX: TJNPY794aSGZf3WGHTna2VCWm2G5Yua7E8  
- USDT (TRC20): TJNPY794aSGZf3WGHTna2VCWm2G5Yua7E8  
- USDT (BEP20): 0x64B28da787BE6ac5889D276A5638d4f077840eC5  
- USDT (ERC20): 0xe455e21a085ae195a097cd4f456051a9916a5064  
- TON: UQAc9zgnnzwS8yb5wxAu5CB0RddmjPBjWI-n46oQ7XfCQrgI  
- XMR: 48QsMjqfkeW54vkgKyRnjodtYxdmLk6HXfTWPSZoaFPEDpoHDwFUciGCe1QC9VAeGrgGw4PKNAksX9RW7myFqYJQDN5cHGT  

---

## Support

- FAQ: check this README first  
- Telegram (International): [@SmartTubeEN](http://t.me/SmartTubeEN)  
- Discord (International): [SmartTube Official](https://discord.gg/Wt8HDDej5z)  
- Telegram RU/UA: [@SmartTubeUA](http://t.me/SmartTubeUA)  
- Email: firsth<!-- abc@def -->ash@gmai<!-- @abc.com -->l.com  

English only; friendly community.

---

## Team

SmartTube is developed by a single developer. Some contributors helped with translations: [GitHub](https://github.com/yuliskov/SmartTube/graphs/contributors).

---

## Build

**Requires OpenJDK 14 or older. Newer JDKs may crash the app.**

```bash
git clone https://github.com/yuliskov/SmartTube.git
cd SmartTube
git submodule update --init
adb connect <device_ip_address>
gradlew clean installStstableDebug
