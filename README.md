# Walezi 🐼💎🐰

Android game for learning letter sounds.

Corresponding [EGRA skill](https://github.com/elimu-ai/model/blob/master/src/main/java/ai/elimu/model/v2/enums/content/LiteracySkill.java): `LETTER_IDENTIFICATION`
> Letter-sound identification tests the actual knowledge students need to have to be able to decode words—i.e., knowing the sound the letter represents allows students to sound out a word.
    
> ![EGRA_LETTER_IDENTIFICATION.png](https://raw.githubusercontent.com/elimu-ai/webapp/master/src/main/webapp/static/img/admin/EGRA_LETTER_IDENTIFICATION.png)

## Screenshots 📸

<img width="640" alt="Walezi" src="https://user-images.githubusercontent.com/15718174/163380593-f661b6e7-c331-4bcb-a87d-a0021a92ae10.png" />

## Demo Videos 🎥

[![](https://i.ytimg.com/vi/1yFMCvpfygE/hqdefault.jpg)](https://youtu.be/1yFMCvpfygE)

[![](https://i.ytimg.com/vi/KinOkMc1kpQ/hqdefault.jpg)](https://youtu.be/KinOkMc1kpQ)

## Build & Run 🔨

### Prerequisites

- Android SDK (API 33 platform and build-tools)
- Java 17 (or 11+)
- Git

### Clone

```bash
git clone --recursive https://github.com/elimu-ai/walezi-android.git
cd walezi-android
```

If already cloned without `--recursive`:

```bash
git submodule update --init
```

### Build

```bash
# All variants (debug)
./gradlew assembleDebug

# Specific variant
./gradlew assembleFurguardiansDebug
./gradlew assembleBotsnboltsDebug
./gradlew assembleBoardDebug
```

### Install on device

```bash
./gradlew installFurguardiansDebug
```

### APK output

```
build/outputs/apk/furguardians/debug/walezi-android-furguardians-debug.apk
build/outputs/apk/botsnbolts/debug/walezi-android-botsnbolts-debug.apk
build/outputs/apk/board/debug/walezi-android-board-debug.apk
```

### Game variants

| Flavor | Package | Description |
|--------|---------|-------------|
| `furguardians` | `org.pandcorps.furguardians` | Fur Guardians |
| `botsnbolts` | `org.pandcorps.botsnbolts` | Bots 'n Bolts |
| `board` | `org.pandcorps.board` | 2-Player Games For 1 Device |

## Installation

> [!IMPORTANT]
> Note: This app depends on the [elimu.ai Content Provider](https://github.com/elimu-ai/content-provider) to be installed.

---

<p align="center">
  <img src="https://github.com/elimu-ai/webapp/blob/main/src/main/webapp/static/img/logo-text-256x78.png" />
</p>
<p align="center">
  elimu.ai - Free open-source learning software for out-of-school children ✨🚀
</p>
<p align="center">
  <a href="https://elimu.ai">Website 🌐</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/elimu-ai/wiki#readme">Wiki 📃</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/orgs/elimu-ai/projects?query=is%3Aopen">Projects 👩🏽‍💻</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/elimu-ai/wiki/milestones">Milestones 🎯</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/elimu-ai/wiki#open-source-community">Community 👋🏽</a>
  &nbsp;•&nbsp;
  <a href="https://www.drips.network/app/drip-lists/41305178594442616889778610143373288091511468151140966646158126636698">Support 💜</a>
</p>
