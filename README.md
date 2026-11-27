# WifiMic — Android App (.apk) & Windows App (.exe)

Two standalone apps that connect automatically over WiFi with one button:
- **WifiMic Android App (`WifiMic-Android.apk`)** — low-latency UDP microphone streaming (~15–25ms), works even when the phone screen is turned off.
- **WifiMic Windows App (`WifiMic.exe`)** — receives your phone's voice and routes it into [VB-CABLE](https://vb-audio.com/Cable/) so Discord, Zoom, Google Meet, Chrome, OBS, and games see your phone as a real PC microphone.

## Free Auto-Build on GitHub (Get `.apk` + `.exe` in ~3 Minutes)
1. Create a new repository on [GitHub](https://github.com/new) (Public or Private — both include free GitHub Actions minutes).
2. Upload all extracted files from this folder (make sure the `.github` folder is included!) and commit to `main`.
3. Open the **Actions** tab in your GitHub repository → click **Build WifiMic Android APK & Windows EXE**.
4. Wait ~3 minutes for both green checkmarks, then scroll down to **Artifacts** and download:
   - **`WifiMic-Android-APK`** → unzip and install `WifiMic-Android.apk` on your Android phone.
   - **`WifiMic-Windows-EXE`** → unzip and double-click `WifiMic.exe` on your Windows PC.
