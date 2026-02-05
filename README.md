# 🌌 zenith_loadingscreen

**The ultimate first impression for your FiveM server.** `zenith_loadingscreen` is a premium-quality, feature-rich loading sequence designed to give your players a high-end experience from the moment they connect. While other "free" scripts are basic, Zenith offers professional-grade features at zero cost.

---

## ✨ Features

* **🎥 Custom Video Support:** Ditch the static images. Support for high-quality loopable video backgrounds.
* **🎶 Integrated Audio Suite:** Custom music support with a built-in volume controller and mute toggle for player comfort.
* **👤 Discord Staff Integration:** Show off your team! Display staff members using their **real Discord profile pictures** for a professional community feel.
* **🎨 100% Customizable:** Every color, text element, and link can be adjusted to match your server's branding perfectly.
* **⏳ Seamless Transitions:** The screen stays active through the entire connection process, including the "bridge," ensuring a smooth hand-off to the game.
* **📱 Fully Responsive:** Looks crisp on everything from 1080p to 4K Ultrawide monitors.
* **⚡ Lightweight:** Optimized code ensures zero impact on your server's loading speed.

---

## 📸 Preview

![Zenith Loading Screen Preview](<img width="1908" height="942" alt="image" src="https://github.com/user-attachments/assets/02db701d-34f9-4bde-9ed5-049764c5def0" />) 
*(Replace this link with your uploaded image link or add it to your GitHub 'images' folder)*

---

## 🛠️ Installation

1.  **Download** the latest version of `zenith_loadingscreen`.
2.  **Extract** the folder into your server's `resources` directory.
3.  **Configure** your settings in the `config.js` or `config.lua` (depending on your setup).
    * Add your YouTube/Video links.
    * Set your Discord Webhook/API for profile photos.
    * Adjust colors to your liking.
4.  Add `ensure zenith_loadingscreen` to your `server.cfg`.
5.  **Restart** your server and enjoy!

---

## ⚙️ Configuration Snippet

```javascript
// Example of how easy it is to customize
const config = {
    serverName: "Zenith Roleplay",
    discordLink: "discord.gg/zenith",
    primaryColor: "#00eeff", // That signature Cyan glow
    useDiscordImages: true,
    music: "sounds/loading_theme.mp3"
};
