# 🎤 VocaList - Voice-to-Todoist AI Assistant

<div align="center">

<!-- Add your logo here -->
![VocaList Logo](assets/logo.png)

*Transform your voice into organized tasks with the power of AI* ✨

[![GitHub stars](https://img.shields.io/github/stars/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=for-the-badge&logo=github&color=ff6b6b)](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=for-the-badge&logo=github&color=4ecdc4)](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/network)
[![License](https://img.shields.io/github/license/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=for-the-badge&color=45b7d1)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)](https://github.com/tenacious7)

</div>

---

## 🚀 What is VocaList?

Ever wished you could just *speak* your tasks and have them magically appear in your to-do list? **VocaList** makes that dream a reality! 

This AI-powered Telegram bot transforms your voice messages into perfectly structured Todoist tasks, complete with:
- 🧠 **Smart priority detection** (1-4 levels)
- 📅 **Automatic due date parsing**
- 🎯 **Context-aware task creation**
- ⚡ **Lightning-fast processing**

> *"Siri, but for productivity ninjas!"* - Built by **Brijesh**

---

## 🎬 See It In Action

### 📹 Demo Videos

<div align="center">

**🔗 LinkedIn Feature Showcase**
> [Watch the LinkedIn post video](YOUR_LINKEDIN_POST_VIDEO_LINK)

**🎥 Full Demo & Tutorial** 
> [Complete walkthrough video](assets/demo-video.mp4)

*Click the links above to see VocaList in action!*

</div>

---

## ✨ Key Features

<table>
<tr>
<td width="50%">

### 🎙️ **Voice Intelligence**
- Multi-language voice recognition
- Background noise filtering
- Natural speech processing
- Instant transcription

</td>
<td width="50%">

### 🧠 **AI-Powered Parsing**
- Context-aware task extraction
- Smart priority assignment
- Due date intelligence
- Auto-categorization

</td>
</tr>
<tr>
<td width="50%">

### ⚡ **Lightning Fast**
- Sub-5 second processing
- Real-time notifications
- Instant task creation
- Zero-delay confirmations

</td>
<td width="50%">

### 🔗 **Seamless Integration**
- Direct Todoist sync
- Telegram bot interface
- Cross-platform compatibility
- Cloud-based processing

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

![n8n](https://img.shields.io/badge/n8n-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI Whisper](https://img.shields.io/badge/OpenAI%20Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Todoist](https://img.shields.io/badge/Todoist-E44332?style=for-the-badge&logo=todoist&logoColor=white)

</div>

### Architecture Highlights:
- **🔄 n8n Workflow Automation** - Visual workflow orchestration
- **🤖 Google Gemini AI** - Advanced natural language understanding  
- **🎵 OpenAI Whisper** - State-of-the-art speech recognition
- **📱 Telegram Bot API** - Seamless messaging interface
- **✅ Todoist API** - Direct task management integration
- **🔄 CloudConvert** - Audio format optimization

---

## 🚀 Quick Start

### Prerequisites
```bash
✅ n8n instance (cloud or self-hosted)
✅ Telegram Bot Token
✅ Todoist API Key
✅ HuggingFace API Key
✅ OpenRouter API Key
✅ CloudConvert API Key
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant.git
   cd VocaList-Voice-to-Todoist-AI-Assistant
   ```

2. **Import workflow to n8n**
   - Open your n8n instance
   - Import `vocalist-workflow.json`
   - Configure all credential nodes

3. **Set up your APIs**
   - Replace all placeholder API keys
   - Test each connection
   - Activate the workflow

4. **Start using VocaList!**
   - Send a voice message to your Telegram bot
   - Watch the magic happen ✨

> 📖 **Detailed setup guide:** [SETUP.md](SETUP.md)

---

## 💬 Usage Examples

### 🎤 Voice Input Examples:
```
🗣️ "Remind me to buy groceries tomorrow at 6 PM, high priority"
✅ Creates: "Buy groceries" | Priority: 1 | Due: Tomorrow 18:00

🗣️ "I need to finish the project report by Friday"  
✅ Creates: "Finish project report" | Priority: 2 | Due: This Friday

🗣️ "Call mom this weekend, not urgent"
✅ Creates: "Call mom" | Priority: 4 | Due: This weekend
```

---

## 📊 Workflow Overview

<div align="center">

![Workflow Diagram](assets/workflow-diagram.png)

*VocaList's intelligent processing pipeline*

</div>

### Process Flow:
1. 📱 **Telegram receives voice message**
2. 🔄 **Audio format conversion & optimization**  
3. 🎵 **Whisper transcribes speech to text**
4. 🧠 **Gemini AI analyzes and structures task**
5. ✅ **Todoist creates the organized task**
6. 📲 **Confirmation sent back to user**

---

## 🎯 Roadmap

### 🔜 Coming Soon:
- [ ] **Multi-task parsing** from single voice message
- [ ] **Project/label auto-assignment** 
- [ ] **Recurring task detection**
- [ ] **Voice task editing capabilities**
- [ ] **Multiple language support**
- [ ] **Slack/Discord integrations**

### 💡 Future Vision:
- [ ] **Calendar integration** (Google/Outlook)
- [ ] **Smart scheduling suggestions**
- [ ] **Team collaboration features**
- [ ] **Analytics & productivity insights**
- [ ] **Mobile app companion**

---

## 🤝 Contributing

Love VocaList? Here's how you can help make it even better:

### 🌟 Ways to Contribute:
- 🐛 **Report bugs** via [Issues](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/issues)
- 💡 **Suggest features** in [Discussions](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/discussions)
- 🔧 **Submit pull requests** with improvements
- 📖 **Improve documentation**
- ⭐ **Star the repo** to show your support!

### Development Setup:
```bash
# Fork the repo
git fork https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant

# Create feature branch
git checkout -b feature/awesome-feature

# Make your changes and commit
git commit -m "Add awesome feature"

# Push and create PR
git push origin feature/awesome-feature
```

---

## 🏆 Achievements & Recognition

<div align="center">

### 📈 **Project Stats**
![GitHub Repo stars](https://img.shields.io/github/stars/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=social)
![GitHub forks](https://img.shields.io/github/forks/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant?style=social)


---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License - Feel free to use, modify, and distribute!
```

## 💝 Support the Project

If VocaList has boosted your productivity, consider:

<div align="center">

⭐ **Star this repository**
🔄 **Share with friends** 
💬 **Spread the word**
☕ **[Buy me a coffee](YOUR_COFFEE_LINK)**

</div>

---

<div align="center">

### 🎤 **Ready to transform your voice into organized tasks?**

[🚀 **Get Started Now**](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/blob/main/SETUP.md) | [📖 **Read the Docs**](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/wiki) | [💬 **Join Community**](https://github.com/tenacious7/VocaList-Voice-to-Todoist-AI-Assistant/discussions)

---

**Made with ❤️ by Brijesh | © 2024 VocaList**

*"Speak your tasks, live your dreams"* ✨

</div>
