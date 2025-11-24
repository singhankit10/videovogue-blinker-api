# VideoVogue Blinker API & SDK

🎬 **Production-ready API & SDK for interactive video product blinkers** - A plug-and-play solution to add shoppable product overlays to any video player.

## 🌟 Features

- **Player Agnostic**: Works with any HTML5 video player, YouTube, Vimeo, or custom players
- **Interactive Product Blinkers**: 4 types of product overlays (Descriptions, Cards, Highlights, Collections)
- **Purpose-Based Behavior**: Advertisement vs Entertainment modes
- **Time-Synchronized**: Auto-sync with video playback timeline
- **Secure API**: JWT authentication, rate limiting, and best practices
- **Analytics Ready**: Track user interactions and engagement
- **Responsive**: Mobile and desktop optimized
- **CDN Ready**: Lightweight SDK (~50KB gzipped)

## 🚀 Quick Start

### For Developers Using the SDK

```html
<!-- Include the SDK -->
<script src="https://cdn.videovogue.ai/sdk/v1/videovogue-sdk.min.js"></script>
<link rel="stylesheet" href="https://cdn.videovogue.ai/sdk/v1/videovogue-sdk.css">

<!-- Your video player -->
<video id="myVideo" src="your-video.mp4" controls></video>

<!-- Initialize -->
<script>
  const blinkers = new VideoVogueSDK({
    apiKey: 'your-api-key',
    videoId: 'your-video-id',
    videoElement: document.getElementById('myVideo'),
    purpose: 'Advertisement' // or 'Entertainment'
  });
</script>
```

## 📁 Project Structure

```
videovogue-blinker-api/
├── backend/          # Node.js REST API
├── sdk/              # Frontend JavaScript SDK
├── demo/             # Demo implementation
└── docs/             # Documentation
```

## 🛠️ Tech Stack

**Backend:**
- Node.js + Express
- JWT Authentication
- Rate Limiting
- Winston Logger
- Helmet Security

**Frontend SDK:**
- Vanilla JavaScript (ES6+)
- Zero dependencies
- Webpack bundled
- CSS3 animations

## 📚 Documentation

- [API Documentation](./docs/API.md)
- [SDK Integration Guide](./docs/SDK_INTEGRATION.md)
- [Examples & Use Cases](./docs/EXAMPLES.md)

## 🔧 Development Setup

See individual README files in `/backend` and `/sdk` directories.

## 📄 License

MIT License - See LICENSE file for details

## 🤝 Contributing

Contributions welcome! Please read our contributing guidelines first.

---

Built with ❤️ by VideoVogue Team
