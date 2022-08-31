# aspectratio

If you see black bars on your stream/recording, see the [Aspect Ratio Guide](https://obsproject.com/kb/aspect-ratio-guide) to select the best aspect ratio for your content.


---

# buffering

If your stream is buffering for you or your viewers, check out [Stream Buffering Troubleshooting](https://obsproject.com/kb/stream-buffering-troubleshooting) for advice.


---

# conflicts

Some third-party applications can prevent OBS Studio from being able to capture the screen, audio, or may even cause crashes. See [Known Application Conflicts](https://obsproject.com/kb/known-conflicts) for a list of such applications.


---

# cpu

If you have problems with high CPU usage or encoder overload, follow [Encoding Performance Troubleshooting](https://obsproject.com/kb/encoding-performance-troubleshooting) to improve performance.


---

# filters

You can fine-tune your video and audio sources using filters. To access Filters, you can either:
1. click on the Filters button on the source toolbar, or
2. right click on your source (or click the Gear icon next to an audio source) and select Filters

See the [Filters Guide](https://obsproject.com/kb/filters-guide) for more information.


---

# fpslimit

Running a game without vertical sync (V-Sync) or a frame rate limiter may cause performance issues. This is because all of the GPU's resources are allocated to running your game; there won't be enough resources left for OBS Studio.

[Enable V-Sync or set a reasonable frame rate limit](https://obsproject.com/kb/encoding-performance-troubleshooting#limit-game-framerate) that your GPU can handle without hitting 100% usage. You may also need to [reduce graphics settings](https://obsproject.com/kb/encoding-performance-troubleshooting#reduce-graphical-settings) in the game.


---

# framedrops

If your stream is disconnecting or OBS Studio reports dropped frames, follow [Stream Connection Troubleshooting](https://obsproject.com/kb/stream-connection-troubleshooting) to improve your connection to the stream servers.


---

# gamecapture

To set up Game Capture:
- see the [Game Capture Guide](https://obsproject.com/kb/game-capture-setup-guide)
- see the [Game Capture Source](https://obsproject.com/kb/game-capture-source)

If you have any issues, follow [Game Capture Troubleshooting](https://obsproject.com/kb/game-capture-troubleshooting).


---

# gamedvr

On Windows 10 1803 and prior, we recommend disabling the "Game DVR Background Recording" feature. This will ensure OBS Studio has access to the resources needed for realtime streaming/recording. Follow [Windows Gaming Features Troubleshooting] for instructions.

On Windows 10 1809 (and later) and Windows 11, you can keep safely this feature enabled without impacting OBS Studio performance.


---

# laptop

If you're using OBS Studio 27+ on Windows 10 1809 or earlier, your system must be configured to run OBS Studio on a specific GPU depending on the type of capture you are trying to do. See the [GPU Selection Guide](https://obsproject.com/kb/gpu-selection-guide) for instructions.


---

# macaudio

**macOS 13**

OBS Studio 28+ on macOS 13 (Ventura) and later can [capture desktop and application audio](https://obsproject.com/kb/macos-desktop-audio-capture-guide#capture-audio-on-macos-13-ventura) using the macOS Screen Capture source.

**macOS 10.15 – macOS 12**

On previous versions of macOS and/or OBS Studio, you can [set up an external application to capture desktop audio](https://obsproject.com/kb/macos-desktop-audio-capture-guide#capture-audio-on-previous-versions-of-macos).

For more information, see the [macOS Desktop Audio Capture Guide](https://obsproject.com/kb/macos-desktop-audio-capture-guide).


---

# macelgato

Certain Elgato video capture products are not fully compatible with OBS Studio on macOS. However, the following workarounds allow you to use these devices:

- **Elgato HD & HD60**: use a macOS Screen Capture/Window source to capture the Elgato Game Capture app running in full screen window mode.
- **Elgato HD60 S**: on Intel-based Macs, use the above method **or** [OBS Link](https://help.elgato.com/hc/articles/360031363132), an NDI-based workaround that adds compatibility with OBS Studio. This device is **not** compatible with Apple Silicon-based Macs.
- **Elgato HD60 S+, Cam Link**: you do not need any special apps to use this device with OBS Studio.
- **Elgato 4K60 S+**: this device is only compatible with Windows; you can use it on an Intel-based Mac running Boot Camp.

---

# macpermissions

OBS Studio requires permission to:

- capture your screen
- capture content from a webcam or capture card
- capture from your audio devices, such as microphone
- enable hotkeys to work when other apps are focused

To grant OBS Studio these permissions, follow these steps:

**Automatically in OBS Studio 28**

1. Click on the **OBS Studio** menu (next to the Apple menu)
2. Click on **Review App Permissions**
3. Click on the buttons and follow the prompts

**Manually**

1. Open System Preferences / System Settings
2. Click on the **Security & Privacy** (10.15 - 12) button or **Privacy & Security** item (13)
    - 10.15 - 12 only: click on the Privacy tab at the top
3. Click on 'Screen Recording', 'Camera', 'Microphone', and 'Accessibility' to manage app permissions
4. Click to enable the permission for OBS Studio


---

# macversions

**OBS Studio 28 supports**

Apple Silicon and Intel
- macOS 13 (Ventura)
- macOS 12 (Monterey)
- macOS 11 (Big Sur)

Intel only
- macOS 10.15 (Catalina)

**Previous versions of macOS**

These versions are no longer supported. To use a supported version, please [update macOS](https://support.apple.com/HT201541) if possible.
- macOS 10.13 (High Sierra) & macOS 10.14 (Mojave): [OBS Studio 27.2.4](https://github.com/obsproject/obs-studio/releases/27.2.4) (Intel only)
- macOS 10.12 (Sierra): [OBS Studio 24.0.6](https://github.com/obsproject/obs-studio/releases/24.0.6)
- macOS 10.11 (El Capitan): [OBS Studio 21.1.1](https://github.com/obsproject/obs-studio/releases/21.1.1)
- macOS 10.10 (Yosemite): [OBS Studio 20.1.0](https://github.com/obsproject/obs-studio/releases/20.1.0)


---

# minecraft

To capture Minecraft: Java Edition on Windows using a Game Capture source:
1. set the Game Capture mode to "Capture specific window"
2. select javaw/minecraft in the "Window" drop down

If you still have issues, follow [Minecraft: Java Edition Troubleshooting](https://obsproject.com/kb/minecraft-java-edition-troubleshooting).


---

# new

If you're new to OBS Studio:
- follow the 5-step [Quick Start Guide](https://obsproject.com/kb/quick-start-guide)
- follow the [Stream Layout Tutorial](https://obsproject.com/kb/stream-tutorial-1-game)
- for more in-depth information, see the [OBS Studio Overview Guide](https://obsproject.com/kb/obs-studio-overview)

If you prefer video guides:
- watch [Nerd or Die's video guide](https://youtube.com/watch?v=5rlrDIwnGGQ&t=0s&list=PLT3Ure7_kYHwj8oT3AV-pZ4_r7yp6mDg-)
- watch [EposVox's OBS Master Class](https://youtube.com/watch?v=nK-Mu7nw5EA&list=PLzo7l8HTJNK-IKzM_zDicTd2u20Ab2pAl)


---

# params

For a list of launch parameters, see [Launch Parameters](https://obsproject.com/kb/launch-parameters).


---

# shortcuts

For a list of keyboard shortcuts, see [Keyboard Shortcuts](https://obsproject.com/kb/keyboard-shortcuts). You can also set your own custom hotkeys in OBS Settings → Hotkeys.


---

# sources

To find out which source(s) to use in your scenes, see the [Sources Guide](https://obsproject.com/kb/sources-guide).


---

# themes

OBS Studio comes with a variety of themes and supports custom, user-made themes. See the [Themes Guide](https://obsproject.com/kb/themes-guide) for more information or download user-made themes from the [OBS Studio forums](https://obsproject.com/forum/resources/categories/themes.10/).


---

# videocall

To share your OBS Studio output with your video call applications such as Discord, Skype, or Teams — including video and audio — follow the [Video Call Streaming Guide](https://obsproject.com/kb/video-call-streaming-guide).

You can also share just video with the [virtual camera](https://obsproject.com/kb/virtual-camera-guide).

---

# virtualcam

OBS Studio provides a virtual camera plugin that allows you to share your OBS Studio output with applications that can make use of a camera, such as Discord, Skype, Teams, etc. See the [Virtual Camera Guide](https://obsproject.com/kb/virtual-camera-guide) to learn how to use the virtual camera.

If the virtual camera is not installed or causing issues in other applications, follow [Virtual Camera Troubleshooting](https://obsproject.com/kb/virtual-camera-troubleshooting).

- **macOS**: follow the [macOS compatibility](https://obsproject.com/kb/virtual-camera-troubleshooting#macos-compatibility) section if you are having issues with specific applications.
- **Linux**: v4l2loopback is required to use the virtual camera. Install it via the `v4l2loopback-dkms` package.

---

# vst

OBS Studio supports most VST 2.x plugins. See the [VST 2.x Plugin Filter](https://obsproject.com/kb/vst-2-x-plugin-filter) page for more information, including restrictions and plugin install paths.


---

# wiki

For information, guides, and troubleshooting instructions for OBS Studio, see:
- [Knowledge Base](https://obsproject.com/kb/) for general information
- [OBS Studio Wiki](https://obsproject.com/wiki/) for developer and contributor information
- [OBS Studio documentation](https://obsproject.com/docs/), our development and scripting API reference


---

