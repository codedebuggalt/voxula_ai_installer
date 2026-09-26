# 🎙️ SPEAK — Voice Dictation & Companion

**Version 2.1** · by Amir Bagawan · Minimalist fullscreen app

---

## Free to Use

SPEAK works right out of the box — no API key required. Want unlimited usage? Just add your own free Gemini API key in **Settings → Setup → Primary API key**.

---

## 🚀 Quick Start

1. **Install it.** Double-click `SPEAK_Setup_v2.1.exe` and follow the wizard. No admin rights needed.

   > 💡 Windows might show an "Unknown publisher" warning — that's normal for new independent apps. Just click **More info → Run anyway**. Nothing installs silently; you'll get a Start Menu entry and an optional Desktop icon.

2. **Launch it** from the Start Menu or Desktop. Settings opens fullscreen with a handy collapsible sidebar.

3. **(Optional) Add your API key.** Paste your Gemini key (starts with `AIzaSy...`), hit **Test**, then **Save**. Grab a free key at [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey).

4. **Start dictating** — press `Ctrl + Space`. Your words appear right where your cursor is, in any app. Press it again to stop.

5. **Multitask with sessions** — `Ctrl + Tab` spawns and switches to a new live session instantly. The Sessions tab shows what's active; oldest sessions get replaced first (max 5 by default).

6. **Talk to your companion** — `Ctrl + /` opens voice (and optional screen sharing). Toggle screen sharing right from the capsule.

7. **Reset when needed** — `Ctrl + Win` clears memory. `Esc` stops live dictation (app keeps running in background).

---

## 🔐 Permissions

Windows requires you to approve these yourself — the installer can't do it for you.

**Microphone**
On first launch, SPEAK checks for mic access. If it's blocked, you'll see a tray alert and a banner in Settings. Click **Grant Permission** to open Windows' privacy settings, allow access, then click **Grant** again to confirm.

**Screen Sharing**
Same idea — SPEAK checks for screen permission before capturing anything. If it's pending or denied, you'll see a banner with a **Grant Permission** button. One click triggers the native prompt for *both* mic and screen.

> ℹ️ Voice dictation still works even if screen sharing is blocked (dictation only needs the mic). If the AI shows blank frames, that means screen permission still isn't granted — fix it in Settings first.

---

## ✉️ Message Verification

Found in **Settings → Preferences**:

| Mode | Behavior |
|---|---|
| **Auto-Send** *(default)* | Types your message and hits Enter automatically |
| **Verification Active** | Types your message, waits for you to hit Enter |

You can also tune **Agent Reasoning** (Low / Medium / High) here. Live sessions always use smart transcription and cursor-aware typing.

---

## 🧪 Self-Tests

Also in **Settings → Preferences**:

- **Test speaker** (Microphone card) — plays a two-tone beep through the real audio path. Hear it clearly? Your speaker setup is good.
- **Test capture** (Live Screen card) — grabs one frame and shows its size + token count. This confirms vision is actually working. A blank result means permission is still blocked.

Something acting weird? Check `%APPDATA%\SPEAK_AI\logs\` and send over the newest `speak-*.log` file — it logs every session event.

---

## 💊 The Capsule

Your hotkeys first open a small pill-shaped indicator — click it (or the maximize button) to expand the full capsule. It stays on top, closes on demand, and only shows up when you trigger a hotkey. You can also find SPEAK sitting quietly in your system tray.

Inside, you'll find a transcript panel (copy, clear, or refine your text) and a screen toggle button. Long status messages truncate neatly, with the full text available on hover.

---

## ✨ Refine Your Text

Just say **"refine"**, **"polish"**, or **"elaborate"** — or tap the buttons in the capsule. Your refined text swaps in automatically, no extra Enter needed. Works in multiple languages, auto-detected.

---

## ❓ Need Help?

Head to **Settings → Help** for:
- Step-by-step guides for Screen Share, Transcription, and Smart Insertion
- A full shortcut cheat sheet
- Quick fixes for cursor focus and permission issues

---

## 💡 Tips

- The capsule only appears when you actually use a hotkey — it won't clutter your screen otherwise.
- Add custom words (names, product terms) and your personal signature in **Settings → Preferences**.
- Set up backup API keys in **Settings → Setup** — SPEAK automatically switches over when you hit a quota limit. Keys are always shown masked.

---

## 🔒 Privacy & Safety

- Your API keys live safely in Windows Credential Manager — never in plain text files.
- Keys are only ever sent to Google, nowhere else.
- A single-instance guard prevents duplicate mics or conflicting hotkeys.
- SPEAK never types into itself when it's the focused window.
- No admin install required. Startup-on-boot is entirely opt-in.

---

## 🗑️ Uninstalling

Go to **Settings → Apps → SPEAK → Uninstall**. That's it.

---

*Made by Amir Bagawan*
