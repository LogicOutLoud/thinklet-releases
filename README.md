# Thinklet for your computer

Your AI, at home on your computer. Use your own supported AI account, API key or private local AI.

[**Download for Mac**](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-mac.dmg) · [**Windows preview**](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-windows-x64.exe) · [**Linux**](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-amd64.deb)

[All release files and checksums](https://github.com/LogicOutLoud/thinklet-releases/releases/latest) · [Installation guide](START-HERE.txt) · [Web app](https://app.thinklet.io)

## Choose your download

| Computer | Download | Other formats |
| --- | --- | --- |
| Mac: Apple silicon or Intel, macOS 13 or later | [Universal Mac disk image](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-mac.dmg) | App ZIP under the release’s Assets |
| Windows: Intel or AMD PC (x64) | [Windows x64 preview installer](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-windows-x64.exe) | Portable ZIP under Assets |
| Windows: ARM64 PC | [Windows ARM64 preview installer](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-windows-arm64.exe) | Portable ZIP under Assets |
| Linux: Intel or AMD PC (amd64/x64) | [Debian/Ubuntu package](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-amd64.deb) | [AppImage](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-amd64.AppImage) · [Portable archive](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-amd64.tar.gz) |
| Linux: ARM64 computer | [Debian/Ubuntu ARM64 package](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-arm64.deb) | [ARM64 AppImage](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-arm64.AppImage) · [Portable archive](https://github.com/LogicOutLoud/thinklet-releases/releases/latest/download/Thinklet-linux-arm64.tar.gz) |

The Mac app is Developer ID signed and Apple-notarized. **Windows downloads are unsigned previews**: Windows may warn about or block them, especially with Smart App Control. Contact support if your computer blocks a package; do not disable security protections to install it. Platform test details are recorded in the release notes.

## Install

**Mac:** Open the disk image, quit an older Thinklet if it is open, and drag **Thinklet.app** into **Applications**. Open it from Applications. If updating, replace the app; your saved library and settings live separately. If macOS reports a damaged, unverifiable or malicious app, stop and contact support. Do not disable Gatekeeper or remove quarantine.

**Windows:** Choose the installer for your processor and run it. It installs for your Windows account and adds Thinklet to Start. The ZIP is portable: extract the entire folder before opening **Thinklet.exe**.

**Linux:** On Debian or Ubuntu, install the downloaded `.deb` with your software installer, or run `sudo apt install ./Thinklet-linux-amd64.deb` (use the ARM64 filename for ARM64 computers). Launch Thinklet from your apps menu. For an AppImage, allow the file to run as a program first. If AppImage dependencies or sandbox restrictions prevent launch, use the `.deb` where supported or contact support. Extract the portable archive completely before running `cabinet-next`.

Follow the welcome screen and choose **Connect your AI**. Enter credentials only inside Thinklet or the provider’s sign-in page. Some integrations depend on the operating system; see the capabilities offered by your copy of Thinklet.

## What’s new

Beta.39 adds Windows and Linux downloads and fixes Claude rejecting imported Thinklet updates because of an empty system block. It includes beta.38’s expanded Discover categories, capability metadata, search and publishing fixes. See the [release notes](https://github.com/LogicOutLoud/thinklet-releases/releases/latest) for changes and verification details.

## Which ZIP is the app?

Use an **app package under a release’s Assets**. GitHub’s green **Code → Download ZIP** button and **Source code** archives download this repository’s instructions; they do not contain an installable app. This public repository contains downloads and instructions. The app’s source is maintained separately.

## Help and updates

Use Thinklet’s Help menu or [email installation support](mailto:chris@logicoutloud.com). Include your OS version, processor and error text. Leave out passwords, API keys and private conversations.

Check **Settings → Help & About → Updates**. Mac, Windows installer and Linux AppImage copies support in-app updates. Portable Windows/Linux archives and Debian packages may require downloading and installing the next package. Choose **Restart and install** when offered; ordinary quitting does not install an update.

To uninstall, quit Thinklet first. On Mac, move Thinklet.app to Trash. On Windows, use Installed apps. On Debian/Ubuntu, remove the `cabinet-next` package. Your saved library and settings are stored separately.

© Logic Out Loud LLC
