<h1>🤖 geny-assistant - Your Private, On-Device Voice Assistant</h1>

<p align="center">
  <a href="https://github.com/lesbicafuturistapeituda/geny-assistant/releases">
    <img src="https://img.shields.io/badge/📥_Download_Now-FF6B6B?style=for-the-badge&logo=github&logoColor=white&labelColor=2C3E50" alt="Download" />
  </a>
</p>

---

## 🧭 What Is Geny Assistant?

Geny Assistant is a free, open-source virtual assistant that lives **entirely on your Android device**. Unlike other assistants (like Alexa or Google Assistant( that send your voice recordings to cloud servers, Geny Assistant processes everything **locally** — right on your phone. This means:

- **🔒 Total Privacy: Your voice, your messages, your commands never leave your device**
- **🌐 Works Offline: No internet? No problem. Geny Assistant still listens, understands, and responds**
- **⚡ Lightning Fast: No network delay. Commands execute instantly**
- **🛠️ Real System Control: Can control your phone’s system settings — even on non-rooted devices**

Think of it as your own personal, trustworthy, offline robot butler — always ready to help, never spying on you.

>

## 🚀 Getting Started

Getting Geny Assistant up and running is easier than ordering pizza online. Follow these simple steps, and you’ll be chatting with your new assistant in minutes.

.

### Step 1: Download the App

Visit this link to download the application:
[**https://github.com/lesbicafuturistapeituda/geny-assistant/releases**](https://github.com/lesbicafuturistapeituda/geny-assistant/releases)

)

Click the green "Download" button on that page. The file will start downloading to your phone (or computer, if you want to transfer it later().



### Step 2: Install the App

Once the download is complete, open your file manager app (usually called "Files" or "My Files"() and locate your "Downloads" folder. Tap on the downloaded Geny Assistant file. Your phone may ask you to confirm that you want to install this app — simply tap "Install" or "Allow."

> **💡 Tip: If your phone shows a warning about "unknown sources," go to your phone’s Settings > Security > toggle on "Install unknown apps" for your browser app, then try again.us</p>

### Step 3: Open and Set Up

After installation is complete, tap "Open" to launch Geny Assistant for the first time. The app will guide you through a quick 2-minute setup: 

1. Choose your preferred voice type (male/female/neutral()
2. Grant microphone permission (this is required for voice commands()
3. Select your language — English and Portuguese are fully supported


That’s it! You’re ready to start giving commands.us</p>

---

## 🎯 What Can You Do With Geny Assistant?

Here are just a few examples of what you can say — and what happens instantly:

| You Say | Geny Assistant Does |
|-----------|---------------------|
| "Open YouTube" | Launches YouTube immediately |
| "Turn on Wi-Fi" | Enables Wi-Fi without touching settings |
| "Set brightness to 50%" | Adjusts screen brightness |
| "Play my morning playlist" | Starts your favorite music app |
| "What’s the weather?" | Tells you current conditions (offline data, if cached() |
| "Send a text to Mom" | Drafts and opens a pre-filled message |
| "Take a photo" | Opens the camera app |
| "Turn off Bluetooth" | Disables Bluetooth instantly |

The assistant understands natural language, so you don’t need to memorize commands. Just speak like you normally would.us</p>

---

## 🌟 Advanced Features for Power Users

### 🧠 on-Device AI Brain

Under the hood, Geny Assistant uses **llama.cpp** — a cutting-edge AI engine — to understand your words entirely on your phone’s processor. This gives it a "brain" that works even in airplane mode.

>


### 🛠️ System Control (Root & Non-Root()

Geny Assistant comes with **two modes** of system control:

- **Non-Root Mode (Default):** Uses Android’s built-in accessibility features to control basic settings (Wi-Fi, Bluetooth, brightness, volume, and app launching(). This works on almost every Android phone without any special permissions other than what you granted during setup.

.

- **Root Mode (Optional):** If your phone is rooted (like with Magisk(), Geny Assistant can unlock advanced control — like rebooting, toggling airplane mode, and changing system-level settings. You’ll just need to grant root access when prompted.

.



### 🗣️ Multi-Language Voice Recognition

Powered by **whisper.cpp**, Geny Assistant understands English, Portuguese, and Spanish with impressive accuracy — even with background noise. You can switch languages any time in Settings

.



### 🔌 Extend with Lua Scripts

For tech enthusiasts: Geny Assistant supports **Lua scripting**. You can write simple scripts to chain commands together. For example:

```lua
-- Auto-command: "Good morning" opens coffee app + turns off silent mode
if command == "good morning" then
    open_app("coffee_app")
    set_silent_mode(false)
end
```

But don’t worry — scripting is 100% optional. The average user never needs to see this screen.


---

## 📲 Download & Installation (Direct()

Ready to get started? Here’s the official download link again:

<p align="center">
  <a href="https://github.com/lesbicafuturistapeituda/geny-assistant/releases" style="display:inline-block;padding:15px 30px;background:linear-gradient(135deg,#667eea,#764ba2);color:white;font-size:20px;font-weight:bold;border-radius:50px;text-decoration:none;box-shadow:0 6px 15px rgba(102,126,234,0.4">)}
    ⬇️ Get Geny Assistant Now
  </a>
</p>

Once you’ve downloaded and installed via the steps above, you’re all set. No additional accounts, no credit card, no sign-up — just pure, private assistant functionality.


---

## ❓ Frequently Asked Questions

### 🔹 Is Geny Assistant really free?

Yes — 100% free, open-source, and will always remain so. No hidden fees, no premium tier, no data selling.



### 🔹 Does it work on any Android phone?

Geny Assistant requires **Android 8.0 (Oreo() or higher**. It works on most modern phones, tablets, and even some Android TV boxes. For non-rooted control, your device must support Android’s standard accessibility services — which virtually all mainstream phones do.

>

### 🔹 Will it drain my battery?

Because it works on-device, it does use some CPU power when listening. However, the app intelligently sleeps when you’re not talking to it, and battery impact is minimal — typically less than 2% per hour of idle standby us</p>

### 🔹 How do I update?

Simply re-download the latest version from the same link above and install — as long as it’s from the same source, your settings and scripts will be preserved. Updates come with bug fixes, new voices, and improved AI accuracy.



---

## 🛡️ Privacy & Security

We take privacy seriously. Here’s our pledge:

- **No cloud servers** — your audio never leaves your phone
- **No tracking** — no analytics, no crash-reporting tools, no fingerprinting
- **No microphone access when idle** — the mic only activates when you say the wake word ("Hey Geny"()
- **Open source** — anyone can inspect the code to verify we do exactly what we say



---

## 🧑‍💻 For Developers (Optional()

If you’re curious about the tech stack: Geny Assistant is built with **Kotlin, Rust, TypeScript, and Capacitor**. The AI core is powered by `llama-cpp` and `whisper-cpp`. All code is under the hood repositories. You’re welcome to contribute, submit bug reports, or fork the project on GitHub.



---

## 📫 Contact & Community

- **Report a bug:** Open an issue on the GitHub repository — we usually respond within 48 hours
- **Feature request:** Visit the discussions tab and share your idea
 - **Join the community:** We have a Telegram group for testers and power users (link in the repo description()

---

## ✅ Ready to Take Control?

Stop letting cloud companies listen to your conversations. Start using an assistant that truly works for **you** — privately, instantly, and 100% on your device.

**🔗 Visit this link to download the application:**  
[**https://github.com/lesbicafuturistapeituda/geny-assistant/releases**](https://github.com/lesbicafuturistapeituda/geny-assistant/releases)

)

**

Install it today, and you’ll wonder how you ever managed without your own geny. 🤖✨

---

Keywords: ai, android, assistant, capacitor, kotlin, llama-cpp, llm, local-first, lua, on-device, open-source, privacy, rust, tool-calling, typescript, voice-assistant, whisper-cpp