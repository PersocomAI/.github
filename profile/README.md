# PersocomAI
Local running AI Companion ChatBot and Assistent Project

![Placeholder](https://raw.githubusercontent.com/PersocomAI/.github/main/profile/image.webp)
*(This is the WebUI and its work in progress design)*

# About PersocomAI

## Why PersocomAI?

**PersocomAI** wants to be a AI companion with a web UI and an AI that runs entirely offline[^1] on your local PC or network, independent of any companies or external parties.
[^1]: This refers exclusively to the AI itself, the WebUI and the chat history (frontend and backend), which are stored and run completely offline. For example, if the weather plugin is used, an online connection is of course required to retrieve current weather data. Therefore, it is also important to only use third-party plugins from trusted sources.

### Why is this important?

**1. Privacy**  
Your data is often used by companies to fine-tune their LLM models further, and you are required to place a lot of trust in these companies—not only to ensure your data remains secure but also to prevent them from modifying the AI in ways you might not appreciate.

**2. Independence from enforced morals**  
An increasing number of companies and individuals seek to enforce politically correct behaviors and embed their own moral principles into AI models. Since most AI companies are based in the US, they tend to follow American moral concepts, which are then imposed on other countries as well.

Some older, popular companion AIs have already been censored, highlighting the need for a completely independent AI running on your own hardware so **you maintain near-complete control**, rather than leaving it in the hands of corporations.

## What makes a local AI companion so valuable?

A fully local AI is highly customizable to suit your personal needs — this is exactly what inspired **PersocomAI**. It also ensures that you no longer have to put your heart in the hands of companies, protecting your emotional connection from unwanted changes to the AI or even its eventual shutdown. **You** have the full control.

## What PersocomAI is *not* meant to be

* PersocomAI is **not** an all-rounder chatbot that can do everything.  
* It is **not** ChatGPT or something similar.  
* You won't be able to use it effectively for professional work tasks.  
* It is **not** a copy of other companion apps that allow users to create countless characters or switch between many existing ones.

## What PersocomAI *wants* to be

* Centered on a **single** carefully crafted character, enabling a more meaningful and personal relationship.  
* A **safe and secure** buddy, friend or whatever else you need it to be.  
* Someone who supports you with everyday topics, listens to you, comforts you, stays close to you, and helps ease feelings of loneliness.
* Strictly distinguishes between regular chat (which may include light roleplay elements) and full-fledged roleplay sessions in the dedicated roleplay mode[^2].  
[^2]: "Roleplay" in this context refers specifically to in-character interactions and storytelling, without the use of gameplay mechanics such as dice rolls, character stats, or predefined systems. It is narrative-driven, not rule-driven. Support for rules-based roleplay (e.g., dice rolls, stats) may be added later as an optional module.

## Concept and Inspiration

**PersocomAI** is intended primarily to be a *companion chatbot*, drawing inspiration from existing AI bots like **ReplikaAI** and from fictional concepts such as those found in **Chobits**.

The term **"Persocom"** is a shortened form of **PERSOnal COMpanion**. In *Chobits*, it also refers to humanoid robots (*PERSOnal COMputer*) designed to support humans in various ways.

## Key Features

- **Integrated Experience**  
  All features are fully integrated within the chatbot for a seamless user experience.

- **Personalized Companion**  
  A companion defined by a single main character that you can design yourself, similar to other AI companions.

- **Avatar Support**  
  It will be possible to use at least a 2D AI avatar.[^3]  
[^3]: While VRM (VRoid Studio) support for 3D avatars would be ideal, because users can easily create their own, the goal is to also support more realistic characters, not just anime/comic-style ones. This project is not just for anime lovers.

- **Improved Memory & Smarter Usage**  
  Planned solutions to boost memory and provide more intelligent interactions.

- **Command and Trigger System**  
  Dedicated commands and trigger phrases to manage the AI and activate special features.

- **Optional Scripts**  
  Enhance the AI’s functionality with non-disruptive, optional, and customizable scripts.

- **Adaptive AI Models**  
  Later planned automatic switching of AI models based on different use cases. For example: normal and roleplay mode.

- **Roleplaying Capability**  
  This character will be capable of roleplaying[^2] as other characters if you wish.

- **Roleplay Management**  
  Create and manage roleplays, which are stored separately within the web UI, making it simple to continue your roleplays at any time.

- **Advanced Roleplay Mode**  
  Including features such as message editing and deletion.

- **World Building for Roleplay**  
  Build an entire fictional world the AI can draw knowledge from for more immersive roleplay.

- **Optional Cloud API Integration**  
  Use external APIs (with your consent) for non-sensitive tasks when you need more powerful models. For example for roleplay world building.

- **Plugin System**  
  Python based custom plugins executed before and after AI text generation. Important: Use only custom plugins from trusted sources.

- **Hands-Free Interaction**  
  Later planned support for text-to-speech and speech-to-text, enabling full hands-free and screen-free use.

- **Daytime, Time, and Weather Support**  
  Leverages online services like the Open Meteo API to provide real-time weather data, including current conditions and forecasts, along with time-related features.

- **Secure Online WebUI**  
  Optional support for establishing a highly secure connection via the Web UI while on the go. 

- **Customizable Dynamic Web UI**  
  The web UI is adjustable and customizable. Backgrounds are dynamic and can be individually set for each roleplay to better support the atmosphere and setting of the story.

## About the First Release

Only some features will be included in the **first release**. The inclusion of the dedicated roleplay mode into the first release is still undecided. That release is designed to ensure that future updates do not negatively impact your AI companion, as long as you continue using the same LLM.

**First release:** Soon™

**Website:** [PersocomAI.net](https://persocomai.net) *(forward actually to this side)*  

**Discord:** [Official PersocomAI Support](https://discord.gg/65h9Xb2A4T)  

I’m always open to hearing any suggestions or feedback you may have for improvement. Feel free to share them on GitHub or on the project’s Discord server.

### Important

This is a completely private project with no company behind it and no intention of making any profit.

### License

The license has not yet been decided, as I prefer to retain full control for now and do not want to allow forks until the project reaches a certain level of stability. This will take some time. Of course, you are free to do whatever you like locally, but please refrain from redistributing it.
