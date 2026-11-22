# NateEFB downloads

**NateEFB** is a tablet-friendly Electronic Flight Bag (EFB) for flight simulation. It runs on your simulator PC and shows up on your iPad: SimBrief flight plans, live route progress, a built-in VATSIM Radar, vPilot messages, runway performance, MSFS and ProSim connections and more.

## Download

1. Open the [latest release](https://github.com/sheerinsane/CaliCrew-EFB-Releases/releases/latest).
2. Download **NateEFB-Setup-*version*.exe** and run it. No GitHub account is needed.
3. Follow the prompts. If Windows SmartScreen warns about an unknown publisher, choose **More info > Run anyway** (the installer is not code-signed yet).
4. Allow NateEFB through Windows Firewall on **Private** networks when asked.
5. In the NateEFB window choose **Connect Tablet**, scan the QR code with your iPad, and use **Share > Add to Home Screen**.

Setup also installs everything NateEFB needs: the Microsoft .NET Framework 4.8 runtime if your PC lacks it, and the NateEFB vPilot plugin if vPilot is installed (close vPilot first).

## Updates

NateEFB checks this page for new versions, downloads them in the background, checks their signature and installs them by itself when your aircraft is not flying, then starts again. You can turn automatic updates off, or ask it to check now, in the **Updates** section of the NateEFB window. Each update is signed; NateEFB refuses anything that does not verify.

Pre-releases are test builds. Tick **Include test builds** in the Updates section to receive them.

A portable ZIP is also provided if you prefer not to install; portable copies tell you about updates but do not install them.
