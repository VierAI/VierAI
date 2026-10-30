<p align="center"><img src="vierai-bunny-192.png" width="96" alt="VierAI bunny" style="image-rendering: pixelated"></p>

<h1 align="center">VierAI</h1>
<p align="center"><b>AI-powered XIV addon forks: features and fixes</b></p>

> [!WARNING]
> **AI "vibe code" disclaimer:** these forks are built with heavy AI assistance. They are tested in real play, but use them at your own risk. They are unofficial and not endorsed by the original authors.

> [!CAUTION]
> **UNINSTALL the official plugin before installing a VierAI fork. Disabling it is NOT enough.**
> A disabled official copy can still clash with the fork (same settings, commands or hooks), and the fork won't work right. In `/xlplugins`, open **Installed Plugins**, find the official version and click **Uninstall**, then install the VierAI-fied one.

## 🧩 Dalamud custom repo

```
https://raw.githubusercontent.com/VierAI/DalamudPlugins/main/vierai.json
```

1. In game, type `/xlsettings` and open the **Experimental** tab.
2. Paste the URL above into an empty **Custom Plugin Repositories** row, then click **+**.
3. Tick **Enabled** and click **Save and Close**.
4. Open `/xlplugins` and search for the plugin.

## 📦 Plugins

| Plugin | Source | Notes |
|---|---|---|
| **PlayerSync** (VierAI-fied) | [VierAI/MareSynchronosClient](https://github.com/VierAI/MareSynchronosClient) | Bug and feature fixes. **Uninstall the official PlayerSync first.** |
| **Customize+** (VierAI-fied) | [VierAI/CustomizePlus](https://github.com/VierAI/CustomizePlus) | Performance fixes to how character bone changes are applied. |
| **XIV Instant Messenger** (VierAI-fied) | [VierAI/XIVInstantMessenger](https://github.com/VierAI/XIVInstantMessenger) | Fixed interface issues and added features such as drag-to-select text (down to single characters, across messages), Ctrl+C and right-click copy, Copy link, and a scroll position that holds while you read back. |
| **Chat 2** (VierAI-fied) | [VierAI/ChatTwo](https://github.com/VierAI/ChatTwo) | Fixed FPS drops with long chat history and added features such as drag-to-select text with Ctrl+C and Copy link, and folding spammy system lines into one clickable line. |
| **Chat Bubbles+** (VierAI-fied) | [VierAI/ChatBubbles](https://github.com/VierAI/ChatBubbles) | Shows chat as the game's own speech bubbles. Replaces the official Chat Bubbles+. |
| **XIVDeck** (VierAI-fied) | [VierAI/XIVDeck](https://github.com/VierAI/XIVDeck) | Use an Elgato Stream Deck as a hotbar. Adds real action and hotbar icons on your keys and lighter hotbar scanning. Needs the XIVDeck Stream Deck plugin too. |
| **Wholist** (VierAI-fied) | [VierAI/Wholist](https://github.com/VierAI/Wholist) | A compact list of nearby players, like WoW's `/who`. |
| **Friend Status Sweep** | [VierAI/FriendStatusSweep](https://github.com/VierAI/FriendStatusSweep) | Original VierAI plugin. Refreshes every off-world friend's online status one at a time and tells you when it's done. |

Versions are always current in `/xlplugins`.

## 🙏 Credits

All credit for the original plugins goes to their authors and communities. These forks only add features and fixes on top of their work. Original authors are welcome to contact me if they would like any change PR'd back upstream.
