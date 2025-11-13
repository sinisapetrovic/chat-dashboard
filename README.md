# 🤖 Chat Dashboard

A free, privacy-first tool to organize your AI conversations across multiple platforms. Keep track of your ChatGPT, Claude, Gemini, and Perplexity chats in one beautiful dashboard.

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)

---

## ✨ Features

### 🎯 Core Functionality
- **Multi-platform support** - Works with Claude, ChatGPT, Gemini, Perplexity, and 20+ other AI platforms
- **Auto-detection** - Paste any AI chat link and the platform is detected automatically
- **Categories & Tags** - Organize conversations by project, topic, or any system that works for you
- **Fuzzy search** - Find chats even with typos (powered by Fuse.js)
- **Multiple views** - Switch between visual grid cards or data-dense table view
- **Status tracking** - Mark chats as active, done, needs review, important, and more

### 💎 Power User Features
- **Drag & drop** - Reorder conversations in table view
- **Bulk operations** - Select multiple chats to move, delete, or export
- **Markdown support** - Add formatted notes with code blocks, lists, and links
- **Keyboard shortcuts** - `Ctrl+K` search, `Ctrl+N` new item, `Esc` close modals
- **Import/Export** - Backup your data as JSON anytime
- **Dark/Light mode** - Automatic based on system preference or manual toggle

### 🔒 Privacy First
- **100% local** - Everything runs in your browser, nothing sent to any server
- **No tracking** - Zero analytics, no "phone home", no data collection
- **No account needed** - No signup, no login, no email required
- **Works offline** - After first load, works completely without internet
- **Your data is yours** - Export anytime, delete anytime, full control

---

## 🚀 Quick Start

### Option 1: Try Online (Recommended)
**https://sinisapetrovic.github.io/chat-dashboard/chat_dashboard_english.html** 

No download needed - just click and start organizing!

### Option 2: Download and Run Locally
1. **Download** (https://github.com/sinisapetrovic/chat-dashboard/blob/main/chat_dashboard_english.html)
2. **Open** the file in any modern browser (Chrome, Firefox, Safari, Edge)
3. **Start adding** your AI chat links
4. That's it! No installation, no setup.

### Option 3: Try with Demo Data
Want to see it in action immediately?
1. Download the dashboard (see Option 2)
2. Download (https://github.com/sinisapetrovic/chat-dashboard/blob/main/chat_dashboard_demo_data.json)
3. Open dashboard → Click **⚙️ Manage** → **Import Data** → Select demo JSON
4. Explore 30 sample conversations across coding, writing, language learning, and more

---

## 🎯 Use Cases

### For Students & Researchers
- Track research conversations by topic or paper
- Organize study sessions by subject
- Keep coding homework help separate from project work
- Reference conversations when writing papers

### For Developers
- Organize coding help by programming language or framework
- Track debugging sessions by project
- Save useful code snippets and explanations
- Keep work and personal coding chats organized

### For Writers
- Manage creative projects across different AI assistants
- Track character development conversations
- Organize worldbuilding notes by story or universe
- Keep research separate from creative writing

### For Language Learners
- Organize practice conversations by language
- Track grammar explanations and examples
- Save useful phrases and idioms
- Monitor progress across different topics

### For Multi-Platform Users
- Stop losing track of which platform you used for what
- Compare responses from different AI assistants
- Keep everything organized in one place
- Easy search across all your conversations

---

## 🛠️ How to Use

### Adding a Chat
1. Copy the URL from any AI chat (Claude, ChatGPT, etc.)
2. Click **➕ New Chat** in the dashboard
3. Paste the link - platform auto-detected!
4. Add a title, pick a category, add notes
5. Save and you're done

### Organizing
- **Categories** - Create custom categories (e.g., "Work", "Learning", "Projects")
- **Tags** - Add multiple tags per chat (e.g., `python`, `debugging`, `urgent`)
- **Status** - Mark as Active, Done, Needs Review, Important, etc.
- **Notes** - Add detailed markdown notes with formatting

### Searching
- **Fuzzy search** - Type in the search box, works even with typos
- **Filter by category** - Click a category in the sidebar
- **Filter by status** - Use the status dropdown
- **Combine filters** - Search + category + status = laser-focused results

### Keyboard Shortcuts
- `Ctrl+K` or `Cmd+K` - Focus search
- `Ctrl+N` or `Cmd+N` - New chat
- `Esc` - Close modal/clear search
- `Ctrl+E` or `Cmd+E` - Toggle theme

### Backup & Export
- Click **⚙️ Manage** → **Export Data**
- Downloads a JSON file with all your data
- Import it back anytime
- Store backups wherever you like (Dropbox, Google Drive, etc.)

---

## 🤔 Frequently Asked Questions

### Is my data safe?
**Yes, absolutely.** Everything runs locally in your browser using localStorage. Your data never leaves your computer. No server, no database, no tracking. You can even disconnect from the internet after loading the page and it works perfectly.

### Can I use this offline?
**Yes!** After the first load (which downloads the Fuse.js library from CDN), the dashboard works completely offline.

### Does it work on mobile?
**Yes!** The dashboard is fully responsive and works on phones and tablets. Though it's designed primarily for desktop use, all features work on mobile browsers.

### Which browsers are supported?
Any modern browser: Chrome, Firefox, Safari, Edge. Tested on the latest versions as of November 2024.

### How much data can I store?
localStorage typically allows 5-10MB per domain, which is enough for thousands of chat entries. If you hit the limit, export and archive old data.

### Can I sync across devices?
Not automatically (there's no cloud backend), but you can export your data from one device and import it on another. Takes 30 seconds.

### Will you add feature X?
Maybe! Open an issue or discussion on GitHub and let's talk about it.

### Can I contribute?
Absolutely! See [Contributing](#-contributing) below.

---

## 🏗️ Technical Details

### Tech Stack
- **Pure vanilla JavaScript** - No frameworks, no build process
- **Fuse.js** - For fuzzy search functionality (only external dependency)
- **localStorage** - For data persistence
- **CSS Variables** - For themeing (dark/light mode)
- **Responsive CSS Grid** - For layouts

### File Structure
```
chat_dashboard_english.html      # Main file (~2,200 lines, 85KB)
chat_dashboard_demo_data.json    # Sample data (30 conversations)
README.md                   # Demo data documentation
```

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Performance
- Loads in <1 second on average connection
- Handles 1000+ chat entries smoothly
- Search results in <100ms
- Minimal memory footprint

---

## 📦 What's Included

### Main Dashboard
- Full-featured chat organization system
- Grid and table views
- Search, filter, and sort
- Dark/light theme toggle
- Import/export functionality

### Demo Data
- 30 realistic sample conversations
- 5 pre-configured categories
- 100+ tags
- Various platforms and statuses
- Perfect for testing and demonstrations

### Documentation
- This README
- Demo data guide
- Quick fix documentation
- Inline code comments

---

## 🎨 Customization

### Adding Your Own Categories
1. Click **⚙️ Manage** → **Categories**
2. Click **➕ New Category**
3. Choose emoji, short key (2-5 letters), and full name
4. Click **Save**

### Supported Platforms (20+)
- ChatGPT (OpenAI)
- Claude (Anthropic)
- Gemini (Google)
- Copilot (Microsoft)
- Perplexity
- HuggingChat
- Poe
- Character.AI
- You.com
- Phind
- And more...

Platform detection is automatic when you paste a link!

---

## 🐛 Known Issues & Fixes

### Browser autocomplete interfering with search
The dashboard automatically disables autocomplete on the search box.

### localStorage full
Export your data, clear old entries, and reimport if needed. Or archive old data to a JSON file.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Bugs
1. Check if the issue already exists
2. Open a new issue with:
   - Clear description of the problem
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser and version

### Suggesting Features
1. Open a discussion or issue
2. Describe the feature and use case
3. Explain why it would be useful
4. Be open to feedback

### Pull Requests
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit PR with clear description

### Code Style
- Use vanilla JavaScript (no frameworks)
- Keep it simple and readable
- Add comments for complex logic
- Test in multiple browsers
- Keep the single-file architecture

---

## 📝 License

**TL;DR:** Free to use, modify, and distribute. Do whatever you want with it!

---

## 🙏 Acknowledgments

- **Fuse.js** - For excellent fuzzy search functionality
- **The AI Community** - For inspiration and feedback
- **You!** - For checking this out and hopefully finding it useful

---

## 💬 Support & Contact

- **Found a bug?** Open an issue
- **Have a question?** Start a discussion
- **Want to chat?** Open a discussion thread

---

## ⭐ Star This Repo

If you find this useful, consider giving it a star! It helps others discover the project.

---

## 🗺️ Roadmap

Potential future features (no promises, no timeline):

- [ ] Cloud sync option (optional)
- [ ] Browser extension
- [ ] Mobile app
- [ ] Conversation preview/summary
- [ ] More AI platform integrations
- [ ] Custom themes
- [ ] Statistics & analytics dashboard

Open to suggestions! What would you like to see?

---

**Made with ❤️ for the AI community**

*Not affiliated with any AI company - just a regular user who got tired of losing track of conversations!*

---

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/YOUR-USERNAME/chat-dashboard?style=social)
![GitHub forks](https://img.shields.io/github/forks/YOUR-USERNAME/chat-dashboard?style=social)
![GitHub issues](https://img.shields.io/github/issues/YOUR-USERNAME/chat-dashboard)
![GitHub last commit](https://img.shields.io/github/last-commit/YOUR-USERNAME/chat-dashboard)

---

**Version 1.0** | Released November 2025 | [Changelog](CHANGELOG.md)

