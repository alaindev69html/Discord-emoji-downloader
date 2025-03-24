# Discord Emoji Downloader

A sleek and modern web application that allows you to easily download emojis and stickers from Discord servers.

![Discord Emoji Downloader](https://i.imgur.com/YOUR_SCREENSHOT.png)

## Features

- 🚀 Download emojis and stickers from any Discord server you have access to
- 🎨 Support for both static and animated emojis
- 📦 Automatic ZIP file generation with organized folders
- 🔒 Secure token handling with visibility toggle
- 📱 Responsive design that works on all devices
- ⚡ Fast downloads with progress tracking
- 🌐 CORS-friendly with automatic proxy fallback

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/discord-emoji-downloader.git
cd discord-emoji-downloader
```

2. Open `index.html` in your web browser or serve it using a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Usage

1. **Get Your Discord Token**
   - Open Discord in your browser
   - Press F12 to open Developer Tools
   - Go to the Network tab
   - Look for a request with your token in the headers
   - Copy the token (starts with "mfa." or other prefix)

2. **Download Emojis**
   - Paste your token in the input field
   - Select a server from the dropdown
   - Choose which emojis/stickers you want to download
   - Click the Download button
   - Your emojis will be saved in a ZIP file

## File Structure

```
emoji/
├── index.html      # Main HTML file
├── app.js         # JavaScript functionality
├── app.css        # Styling
└── manifest.json  # Web app manifest
```

## Dependencies

- [jQuery](https://jquery.com/) - DOM manipulation
- [Semantic UI](https://semantic-ui.com/) - UI components
- [JSZip](https://stuk.github.io/jszip/) - ZIP file generation
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - File download handling
- [Ace Editor](https://ace.c9.io/) - Code editor for manual mode

## Security

- Your Discord token is never stored or transmitted to any third-party servers
- All requests are made directly to Discord's API
- The application runs entirely in your browser

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Discord for their amazing platform and API
- The open-source community for the fantastic libraries used in this project
- All contributors who have helped improve this tool

## Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/yourusername/discord-emoji-downloader/issues) page
2. Create a new issue if your problem isn't already listed
3. Provide as much detail as possible about your problem

---

**Note**: This tool is not affiliated with Discord Inc. Use it responsibly and in accordance with Discord's Terms of Service. 
