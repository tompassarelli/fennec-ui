# 🦊 Fennec UI

![Demo Screenshot](demo.png)

*Clean browsing with integrated Sideberry sidebar - no visual clutter, just pure functionality.*

A clean, minimal Firefox CSS theme designed for **first-class Sideberry support** without the typical Firefox UI baggage. Inspired by the elegant UX philosophy of Zen Browser.

Perfect for users who want the stability of Firefox with the clean aesthetics of modern, minimal browsers.

Transform Firefox into a distraction-free browsing experience that prioritizes:

- **Seamless Sideberry Integration** - Toggle entire Fennec UI with Sideberry's built-in hotkey
- **Minimal Chrome** - Remove unnecessary Firefox UI elements that clutter the experience  
- **Zen-Inspired Design** - Clean, purposeful aesthetics focused on content
- **Distraction-Free Browsing** - Let your content and workflow take center stage

**Security Guardrails**: Even when the UI is completely hidden, shows Not Secure warning

![Demo Screenshot](demo-security.png)

## Installation

1. Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in `about:config`
2. Navigate to your Firefox profile folder

On the Flatpak version of Firefox, location is different

    Open Firefox
    Type about:support in the address bar and press enter
    Look for the Application Basics section.
    Click on Open Profile Folder. This will open the folder which contains your user data.

3. Create a `chrome` folder if it doesn't exist
4. Copy `userChrome.css` to the `chrome` folder
5. Install [Sideberry extension](https://addons.mozilla.org/en-US/firefox/addon/sidebery/)
6. Use sideberry.css in the sideberry custom css settings
7. Install [Userchrome Toggle Extended](https://addons.mozilla.org/en-US/firefox/addon/userchrome-toggle-extended/)
8. Change 'style 1' (hide all ui) to preferred hotkey desired in "manage extension shortcuts"
9. Restart Firefox

### Optional Recommended Extensions
- **[Vimium](https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/)** - Keyboard-driven navigation that complements the minimal, distraction-free interface

## Usage Guide

Utilizing the chosen hotkey for user chrome toggle hides the whole UI

This elegant toggle gives you the best of both worlds - organized tab management when you need it, a clean browsing experience when you don't, and security awareness at all times.

📋 **[Roadmap & Release Notes](https://github.com/tompassarelli/fennec-css/wiki)** - project wiki for roadmap and release notes as inclined.

👾 **[Known Issues & Troubleshooting](https://github.com/tompassarelli/fennec-ui/wiki/Troubleshooting)** - noted some common issues and workarounds 

## 📜 Disclaimer

- This theme modifies Firefox's user interface, which can interfere with security indicators (notably, when the UI is completely hidden)
- **Use at your own risk** - The author is not liable for any security issues, data breaches, or other damages
- **You are responsible** for verifying the security of websites you visit
- Always keep Firefox and your extensions updated
- Consider the security implications before using any userChrome modifications

**By using this theme, you acknowledge these risks and agree that the author bears no responsibility for any consequences.**